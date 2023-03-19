pipeline {
    agent any

    stages {
        stage('Stage 1') {
            steps {
                echo 'Running stage 1..'
            }
        }
        stage('Stage 2') {
            steps {
                echo 'Running stage 2..'
            }
        }
        stage('Stage 3') {
            steps {
                echo 'Running stage 3..'
            }
        }
    }
    post {
        always {
            echo 'pipeline ended'
        }
        failure {
            echo 'pipeline failed'
        }
    }
}
