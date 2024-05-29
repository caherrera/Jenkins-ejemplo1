pipeline {
    agent any
    
    stages {
        stage('Build') {
            steps {
                sh 'docker build -t myimage:latest .'
            }
        }
    }
}