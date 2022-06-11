pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                bat 'dart pub get'
                bat 'dart test'
            }
        }
    }
}