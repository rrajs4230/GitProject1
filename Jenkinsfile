pipeline {
    agent any

    stages {
        stage('Stage 1') {
            steps {
                echo 'Executing Stage 1...'
            }
        }
        
        stage('Stage 2') {
            steps {
                echo 'Executing Stage 2...'
            }
        }

        stage('Stage 3') {
            steps {
                echo 'Executing Stage 3rd...'
            }
        }

        stage('Stage 4') {
            steps {
                echo 'Executing Stage 4...'
            }
        }

        stage('Stage 5') {
            steps {
                echo 'Executing Stage 5...'
            }
        }
    }

    post {
        success {
            echo 'Pipeline completed successfully!'
        }
        failure {
            echo 'Pipeline failed. Check logs for details.'
        }
    }
}
