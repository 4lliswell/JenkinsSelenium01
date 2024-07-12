pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                script {
                    def mvnHome = tool name: 'Maven', type: 'maven'
                    bat "${mvnHome}/bin/mvn clean test"
                }
            }
        }
    }
}
