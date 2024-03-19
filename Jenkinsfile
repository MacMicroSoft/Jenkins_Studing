pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                // Use Maven tool
                withMaven(maven: 'Maven') {
                    sh "mvn clean verify"
                }
            }
        }
    }
}
