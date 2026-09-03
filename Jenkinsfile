pipeline {
    agent any

    stages {
        stage('Code Checkout') {
            steps {
                echo '📥 Checking out code from GitHub repository...'
            }
        }

        stage('Build App') {
            steps {
                echo '🛠️ Building application...'
                sh 'echo "App Version 1.0.0 Built Successfully"'
            }
        }

        stage('Test App') {
            steps {
                echo '🧪 Running unit tests...'
                sh 'echo "Test results: 100% Passed"'
            }
        }
    }

    post {
        success {
            echo '🎉 Jenkinsfile execution successful!'
        }
    }
}
