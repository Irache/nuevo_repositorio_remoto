pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Ask for run') {
            steps {
                input 'continue?'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
                echo 'Oops...'
                exit 1
            }
        }
    }
}