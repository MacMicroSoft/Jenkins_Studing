pipeline {
    agent any
    
    environment {
        APP_PORT=9090
    }
    stages {
        stage('Build') {
            steps {
                sh 'mvn -DskipTests package'
            }
        }
        stage('Unit Test') {
            steps {
                sh 'mvn test'
            }
        }
    }
}
