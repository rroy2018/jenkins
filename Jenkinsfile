pipeline {
    agent any
    
    stages {
        stage('Preparation') {
            steps {
                // Pre-processing action
                sh 'echo "Preparing environment..."'
                // You can add more pre-processing steps here
            }
        }
        stage('Build') {
            steps {
                // Your build steps go here
                sh 'echo "Rishav Build..."'
            }
        }
        stage('Test') {
            steps {
                // Your test steps go here
                sh 'echo "Testing..."'
            }
        }
        stage('Deploy') {
            steps {
                // Your deployment steps go here
                sh 'echo "Deploying..."'
            }
        }
    }
    
    post {
        always {
            // Post-processing action
            sh 'echo "Cleaning up..."'
            // You can add more post-processing steps here
        }
        success {
            // Actions to be executed if the pipeline succeeds
            echo 'Pipeline succeeded!'
        }
        failure {
            // Actions to be executed if the pipeline fails
            echo 'Pipeline failed!'
        }
    }
}
