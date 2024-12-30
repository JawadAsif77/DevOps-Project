pipeline {
    agent any  // Use any available Jenkins agent

    stages {
        // Checkout the code from GitHub
        stage('Checkout') {
            steps {
                checkout scm  // This pulls your repository code from GitHub
            }
        }

        // Build stage (example: building your website)
        stage('Build') {
            steps {
                script {
                    // Example build command for a website (you can replace it with your actual build process)
                    sh 'echo "Building website..."'
                    sh 'npm install'  // Example: If you're using Node.js for your website
                }
            }
        }

        // Test stage (example: running tests)
        stage('Test') {
            steps {
                script {
                    // Example test command (you can replace it with actual test commands)
                    sh 'echo "Running tests..."'
                    sh 'npm test'  // Example: If you're running tests with npm
                }
            }
        }

        // Deploy stage (example: deploying the website)
        stage('Deploy') {
            steps {
                script {
                    // Example deploy command (you can replace this with your actual deploy process)
                    sh 'echo "Deploying website..."'
                    // For example, you might want to deploy the website to a server
                    // or containerized environment here
                }
            }
        }
    }
}
