pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                def username = 'Jenkins'
                echo 'Building..'
                echo "Hello, ${username}"
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}