pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
                sleep 1
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
                sleep 1
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
                sleep 5
                exit 1
            }
        }
    }
}
