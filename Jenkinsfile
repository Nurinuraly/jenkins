pipeline {
    agent any
    stages {
        stage('Clone') {
            steps {
                git 'https://github.com/your-username/your-repo.git'
            }
        }
        stage('Build') {
            steps {
                // Build commands, e.g., for Maven: sh 'mvn clean install'
                echo 'Building...'
            }
        }
        stage('Testing') {
            steps {
                echo 'Testing...'
            }
        }
    }
}
