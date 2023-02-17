pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh 'echo "Building..."'
                // add commands to build your code here
            }
        }

        stage('Test') {
            steps {
                sh 'echo "Testing..."'
                // add commands to run your tests here
            }
        }

        stage('Deploy') {
            steps {
                sh 'echo "Deploying..."'
                // add commands to deploy your code here
            }
        }
    }

    post {
        failure {
            echo 'Pipeline failed'
        }
    }
}
