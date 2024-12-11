pipeline {
    agent any 

    stages {
        stage('Build') {
            steps {
                script {
                    bat 'docker build -t todoapplication .'
                }
            }
        }
        stage('Test') {
            steps {
                script {
                    echo 'Testing ...'
                }
            }
        }
        stage('Deploy') {
            steps {
                script {
                    echo 'Deploying ...'
                }
            }
        }
    }
}