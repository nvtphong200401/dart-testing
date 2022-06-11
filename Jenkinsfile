pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                sh 'dart pub get'
            }
            steps {
                sh 'dart test'
            }
        }
    }
}