pipeline {
    agent any
    stages {
        stage('env info') {
            steps {
                sh 'mvn --version'
                sh 'java --version'
            }
        }
        stage('build') {
            steps {
                sh 'mvn compile'
                sh 'mvn package'
            }
        }
    }
}