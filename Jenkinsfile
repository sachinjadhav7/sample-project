


pipeline {
    agent any 
    stages {
        stage('dir') { 
            steps {
                sh "mkdir fusion" 
            }
        }
        stage('prin') { 
            steps {
					echo "hello devops"
            }
        }
        stage('git') { 
            steps {
                sh "sudo apt install git -y"
            }
        }
    }
}
