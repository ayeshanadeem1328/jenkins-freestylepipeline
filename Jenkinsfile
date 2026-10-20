
pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Build stage started'
                sh 'python3 --version'
            }
        }

        stage('Test') {
            steps {
                echo 'Test stage completed'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploy stage completed'
            }
        }
    }
}
