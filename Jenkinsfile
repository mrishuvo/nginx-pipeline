pipeline {
    agent any
    stages {
        stage('Clone Repository') {
            steps {
                git
            }
        }
        stage('Build') {
            steps {
                // Your build commands, if any
            }
        }
        stage('Deploy') {
            steps {
                sh 'cp index.html /var/www/html/index.html' // Copy index.html to Nginx directory
                sh 'systemctl restart nginx' // Restart Nginx
            }
        }
    }
}
