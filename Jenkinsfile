pipeline {
    agent any
    
    stages {
        stage('Checkout') {
            steps {
                echo 'Code checkout from GitHub'
            }
        }
        stage('Build') {
            steps {
                echo 'Building the project...'
                // Ninte build command ivide idanam. Eg: sh 'npm install'
            }
        }
        stage('Test') {
            steps {
                echo 'Running tests...'
                // Test command: sh 'npm test'
            }
        }
    }
}
