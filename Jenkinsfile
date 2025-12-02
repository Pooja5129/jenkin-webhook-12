pipeline {
    agent any

    stages {
        stage('Clone') {
            steps {
                git 'https://github.com/Pooja5129/jenkin-webhook-12.git'
            }
        }

        stage('Build') {
            steps {
                sh 'echo "Building application"'
            }
        }

        stage('Test') {
            steps {
                sh 'echo "Running tests..."'
            }
        }
    }
}
