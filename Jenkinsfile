
pipeline {
    agent any

    stages {
        stage('Verify Repository') {
            steps {
                echo 'Jenkinsfile is loaded from GitHub!'
                echo 'Checking the project workspace...'

                sh 'pwd'
                sh 'ls -la'
            }
        }

        stage('Build') {
            steps {
                echo 'Build stage executed successfully!'
                echo 'My first pipeline-as-code project is working!'
            }
        }
    }

    post {
        success {
            echo 'Pipeline completed successfully!'
        }

        failure {
            echo 'Pipeline failed. Check the console output.'
        }
    }
}
