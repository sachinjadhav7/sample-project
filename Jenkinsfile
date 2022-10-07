pipeline {
    agent any 
    stages {
     stage ('download httpd') {
					steps {
					
							sh "sudo apt install httpd -y"
							
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
