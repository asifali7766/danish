pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                checkout scm
            }
        }
        stage('Build') {
            steps {
                bat 'echo Building the project...'
            }
        }
        stage('Test') {
            steps {
                bat 'echo Running tests...'
            }
        }
        stage('Notify') {
            steps {
                bat 'echo Build and Test complete!'
            }
        }
    }
}
