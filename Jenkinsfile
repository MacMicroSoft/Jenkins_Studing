pipeline {
    agent any

    environment {
        APP_PORT = '9090'
    }

    stages {
        stage('Build') {
            steps {
                bat 'mvn clean'
            }
        }
        stage('Unit Test') {
            steps {
                bat 'mvn test'
            }
        }
    }
}
