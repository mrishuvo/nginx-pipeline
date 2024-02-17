pipeline {
    agent any
    stages {
        stage('Clone Repository') {
            steps {
                git 'https://github.com/mrishuvo/nginx-pipeline.git'
            }
        }
        stage('Build') {
            steps {
                echo 'Building the project...' // Dummy build step
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying the project...' // Dummy deployment step
            }
        }
    }
}
