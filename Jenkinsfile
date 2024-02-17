pipeline {
    agent any
    stages {
        stage('Clone Repository') {
            steps {
                echo 'Cloning repository...' // Placeholder step, replace with actual Git clone step
            }
        }
        stage('Build') {
            steps {
                echo 'Building project...' // Placeholder step, replace with actual build commands
            }
        }
        stage('Deploy Nginx') {
            steps {
                sh 'cp index.html /usr/share/nginx/html/index.html' // Copy index.html to Nginx directory
                sh 'systemctl restart nginx' // Restart Nginx
            }
        }
    }
}
