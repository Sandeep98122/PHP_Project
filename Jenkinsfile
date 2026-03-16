pipeline {
    agent any

    stages {

        stage('Clone Repository') {
            steps {
                git 'https://github.com/Sandeep98122/PHP_Project.git'
            }
        }

        stage('Install Dependencies') {
            steps {
                sh 'echo Installing dependencies'
            }
        }

        stage('Build') {
            steps {
                sh 'echo Build Stage'
            }
        }

        stage('Test') {
            steps {
                sh 'echo Running Tests'
            }
        }

        stage('Deploy') {
            steps {
                sh 'echo Deploy Stage'
            }
        }
    }
}
