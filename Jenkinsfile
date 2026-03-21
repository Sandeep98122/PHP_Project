pipeline {
    agent any

    stages {

        stage('Clone') {
            steps {
                // Clone repository from Git
                git branch: 'main', url: 'https://github.com/your-username/your-repo.git'
            }
        }

        stage('Build') {
            steps {
                // Example for Node.js project
                sh 'npm install'
                sh 'npm run build'
            }
        }

        stage('Test') {
            steps {
                // Run tests
                sh 'npm test'
            }
        }
    }

    post {
        success {
            echo 'Build and tests passed ✅'
        }
        failure {
            echo 'Something failed ❌'
        }
    }
}
