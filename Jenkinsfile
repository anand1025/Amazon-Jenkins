
pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                echo 'Checking out source code from release branch'
            }
        }

        stage('Build') {
            steps {
                echo 'Testing GitHub webhook trigger'
            }
        }

        stage('Test') {
            steps {
              echo 'GitHub webhook triggered Jenkins automatically'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying the application'
            }
        }

        stage('Release') {
            steps {
                echo 'Release branch pipeline executed successfully'
            }
        }
    }

    post {
        success {
            echo 'Pipeline completed successfully!'
        }
        failure {
            echo 'Pipeline execution failed!'
        }
    }
}
