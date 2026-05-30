pipeline {
    agent any

    triggers {
        pollSCM('H/2 * * * *')
    }

    stages {

        stage('Checkout') {
            steps {
                echo 'Checkout Stage Modified'
            }
        }

        stage('Build') {
            steps {
                bat 'echo Building Application'
            }
        }

        stage('Test') {
            steps {
                bat 'echo Testing Application'
            }
        }

        stage('Deploy') {
            steps {
                bat 'echo Deploying Application'
            }
        }
    }
}