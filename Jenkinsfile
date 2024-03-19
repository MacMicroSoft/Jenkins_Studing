pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh "mvn clean verify"
            }
        }
        stage('Unit Test') {
            steps {
                sh 'mvn test'
            }
        }
    }
}
