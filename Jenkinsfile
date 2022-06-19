pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                bat 'dart pub get'
            }
        }
        stage('test') {
            steps {
                bat 'dart test'
            }
        }
    }
    post {
        failure {
            mail to: 'nvtphong19@clc.fitus.edu.vn',
            subject: "You are a failure, even your code is a failure",
            body: "You should be fired because of your failure"
        }
    }
}