pipeline {
    agent any

    stages {
        stage('Docker') {
            steps {
                bat 'docker build -t myapp .'
            }
        }
        
    }
}