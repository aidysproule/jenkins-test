pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building.. ${env.BUILD_NUMBER}'
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
