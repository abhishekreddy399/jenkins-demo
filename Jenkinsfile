pipeline {
    agent any

    stages {

        stage('Checkout') {
            steps {
                echo 'Pulling source code from GitHub'
            }
        }

        stage('Build') {
            steps {
                echo 'Building website'
                sh 'ls -l'
            }
        }

        stage('Test') {
            steps {
                echo 'Testing website'
                sh 'grep "Jenkins CI" index.html'
            }
        }
    }
}
