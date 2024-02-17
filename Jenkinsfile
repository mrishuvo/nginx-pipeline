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
                sh 'sudo cp index.html /var/www/html/index.html' // Copy index.html to Nginx directory
                sh 'sudo systemctl restart nginx' // Restart Nginx
            }
        }
    }
}
