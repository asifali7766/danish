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
                echo 'Building the project...'
                sh 'echo Build done'
            }
        }
        stage('Test') {
            steps {
                echo 'Running tests...'
                sh 'echo Tests passed'
            }
        }
        stage('Notify') {
            steps {
                echo 'Build and Test complete!'
            }
        }
    }
}
Add Jenkinsfile for pipeline demo
