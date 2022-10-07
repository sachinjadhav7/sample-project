pipeline {
    agent any 
    stages {
     stage ('print') {
					steps {
					
							echo "hello-world"
							
							}
							}
							
        stage('Test') { 
            steps {
                echo "pwd"
            }
        }
        stage('Deploy') { 
            steps {
                sh "git status" 
            }
        }
    }
}
