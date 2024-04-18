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
                echo 'Poll request should be initiated after every 1 min from Jenkins.
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
                echo 'Being deployed after every 1 min.
            }
        }
    }
}
