pipeline {
    agent any

    stages {
        stage('Clone Repo') {
            steps {
                echo 'Cloning repository...'
                checkout scm
            }
        }
        stage('Build') {
            steps {
                echo 'Building the project...'
                // No actual build step needed for static HTML
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying the project...'
                // We can enhance this with GitHub Pages or another deploy later!
            }
        }
    }
}
