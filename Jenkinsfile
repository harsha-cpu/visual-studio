pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/your-username/your-repo.git'
            }
        }
        stage('Build') {
            steps {
                echo 'Building...'
                // Example for Node.js: run npm install
                sh 'npm install'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing...'
                // Example for Node.js: run tests
                sh 'npm test'
            }
        }
    }
}
