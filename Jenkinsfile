pipeline {
    agent {
        // Specify the user that has the necessary permissions
        node {
            label 'my-label'
            customWorkspace '/var/lib/jenkins/workspace/nginx-pipeline'
        }
    }
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
                sh 'cp index.html /var/www/html/index.html' // Copy index.html to Nginx directory
                sh 'systemctl restart nginx' // Restart Nginx
            }
        }
    }
}
