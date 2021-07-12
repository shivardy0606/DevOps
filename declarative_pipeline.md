pipeline{
        agent any
        environment{
            PATH = "/opt/maven/bin:$PATH"
        }
		stages{
		      stage('git'){
		          steps{
			         git credentialsId: 'git', url: 'https://github.com/shivardy0606/boi.git'
		          }
			  }
			   stage('build'){
		          steps{
			         sh "mvn clean install"
		          }
			  }
			  stage('deploy'){
		          steps{
			         deploy adapters: [tomcat9(credentialsId: 'tomcat', path: '', url: 'http://13.232.213.136:8080/')], contextPath: '/test01', war: '**/*.war'
		          }
			  }
			 
		}
}
