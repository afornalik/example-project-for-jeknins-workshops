pipeline {
    agent any
    stages {
        stage('env info') {
            steps {
                sh 'mvn --version'
            }
             steps {
                sh 'java --version'
            }
        }
    }
}