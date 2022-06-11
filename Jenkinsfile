pipeline {
    agent {
        docker { image 'dart' }
    }
    stages {
        stage('build') {
            steps {
                bat 'dart pub get'
                bat 'dart test'
            }
        }
    }
}