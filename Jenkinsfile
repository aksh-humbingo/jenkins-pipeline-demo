pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building the project...'
            }
        }

        stage('Test') {
            steps {
                echo 'Running tests...'
            }
        }

        stage('Deploy') {
            steps {
                echo '🚀 Sucessfully Deployed to production!'
            }
        }

        stage('Notify') {
            steps {
                echo '📣 Sending Slack notification...'
            }
        }
    }
}
