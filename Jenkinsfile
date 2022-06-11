pipeline {
    agent any
    stages {
        stage('build') {
            agent {
                docker {
                    image 'dart'
                }
            }
            steps {
                bat 'dart pub get'
                bat 'dart test'
            }
        }
    }
}