pipeline {
    agent any
    stages {
        stage('Clone Repository') {
            steps {
                git branch: 'main', 
                    url: 'https://github.com/JawadAsif77/DevOps-Project.git',
                    credentialsId: 'github-credentials'  // Use the ID you added in Step 2
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deployment stage!'
            }
        }
    }
}
