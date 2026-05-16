pipeline {
    agent any

    stages {

        stage('Clone') {
            steps {
                echo 'Downloading code...'
            }
        }

        stage('Build') {
            steps {
                sh 'mvn package'
            }
        }

        stage('Test') {
            steps {
                sh 'echo "Testing Passed"'
            }
        }

        stage('Deploy QA') {
            steps {
                sh 'echo "Deploying to QA"'
            }
        }

        stage('Deploy PROD') {
            steps {
                sh 'echo "Deploying to PROD"'
            }
        }
    }
}
