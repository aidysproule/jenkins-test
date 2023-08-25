pipeline {
    agent any
    environment {
        EXAMPLE_CREDS = credentials('secure-password')
    }
    stages {
        stage('Build') {
            steps {
                echo "Building.. ${env.BUILD_NUMBER}"
                echo "Creds ${EXAMPLE_CREDS_USR}:${EXAMPLE_CREDS_PSW}"
                echo 'Creds ${EXAMPLE_CREDS_USR}:${EXAMPLE_CREDS_PSW}'
            }
        }
        stage('Test') {
            steps {
                echo "Testing.."
            }
        }
        stage('Deploy') {
            steps {
                echo "Deploying...."
            }
        }
    }
}
