pipeline {
    agent any 
    stages {
     stage ('print') {
					steps {
					
							echo "hello-devops"
							
							}
							}
							
        stage('curret') { 
            steps {
                echo "pwd"
            }
        }
        stage('status') { 
            steps {
                sh "git status" 
            }
        }
    }
}
