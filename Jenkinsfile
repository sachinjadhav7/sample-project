pipeline {
    agent any 
    stages {
        stage('git-scm pull') { 
            steps {
					cleanWs()
					git 'https://github.com/sachinjadhav7/devops.git'
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
