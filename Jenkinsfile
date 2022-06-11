pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                bat 'dart pub get'
            }
            steps {
                bat 'dart test'
            }
        }
    }
}