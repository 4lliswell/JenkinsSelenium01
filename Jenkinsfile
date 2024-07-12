pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                echo 'Compiling the MVN source code'
                bat 'mvn clean test'
            }
        }
    }
}
