pipeline {
    agent any
    stages {
        stage('Checkout and Clone') {
            steps {
                git branch: 'main', url: 'https://github.com/All-Father06/scripted-pipeline.git'
            }
        }
        stage('Build') {
            steps {
                bat 'echo "Building the code"'
            }
        }
        stage('Deploy') {
            steps {
                bat 'copy *.html C:\\xampp\\htdocs\\ce.html'
            }
        }
    }
}