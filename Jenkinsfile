//Fist file
pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                bat 'echo "Hello World"'
                bat '''
                    echo "Multiline shell steps works too"
                    
                '''
            }
        }
        stage('SIT') {
            steps {
                bat 'echo "Testing"'
            }
        }
        stage('UAT') {
            steps {
                bat 'echo "Testing"'
            }
        }
        stage('Deploy') {
            steps {
                bat 'echo "Deploying"'
            }
        }
    }
