pipeline {
    agent any

    stages {
        stage('Clone') {
            steps {
                echo 'Cloning repository from GitHub...'
            }
        }
        stage('Build') {
            steps {
                echo 'Building your application...'
                // Add your build commands here, e.g., sh 'mvn clean package'
            }
        }
        stage('Test') {
            steps {
                echo 'Running unit tests...'
                // Add your test commands here, e.g., sh 'npm test'
            }
        }
    }
}