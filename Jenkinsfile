pipeline {
    agent any

    stages {
        stage('Clone') {
            steps {
                git 'https://github.com/Sandeep98122/PHP_Project.git'
            }
        }

        stage('Build') {
            steps {
                sh 'php -v'
            }
        }

        stage('Test') {
            steps {
                sh 'echo "Run tests here"'
            }
        }
    }
}
