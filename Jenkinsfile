pipeline {
    agent any
    stages {
        stage('Clone Repository') {
            steps {
                git branch: 'main', url: 'https://github.com/username/repository.git'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Website deployed! You can now access it via Jenkins workspace URL.'
            }
        }
    }
}
