pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                // Pull the latest code from GitHub
                git 'https://github.com/your-username/your-repo.git'
            }
        }
        stage('Build') {
            steps {
                // For demonstration purposes, just echo a message
                sh 'echo "Building project..."'
            }
        }
        stage('Testing') {
            steps {
                // For demonstration purposes, just echo a message
                sh 'echo "Running tests..."'
            }
        }
    }
}
