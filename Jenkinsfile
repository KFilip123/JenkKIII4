pipeline {
    agent any

    stages {
        stage('Clone') {
            steps {
                git credentialsId: 'github-token', url: 'https://github.com/<your-username>/jenkins-blueocean-demo.git'
            }
        }
        stage('Build') {
            steps {
                echo 'Building the project...'
                sh 'ls -l'
            }
        }
        stage('Test') {
            steps {
                echo 'Running tests...'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploy step (placeholder)...'
            }
        }
    }
}
