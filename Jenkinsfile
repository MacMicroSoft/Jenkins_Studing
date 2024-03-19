pipeline {
    agent any
    
    environment {
        APP_PORT=9090
    }
    stages {
        stage('Build') {
            steps {
                mvn -DskipTests package
            }
        }
        stage('Unit Test') {
            steps {
                 mvn test
            }
        }
    }
}
