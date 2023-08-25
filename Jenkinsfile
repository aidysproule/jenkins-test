pipeline {
    agent any
    environment {
        EXAMPLE_CREDS = credentials('secure-password')
    }
    stages {
        stage('Build') {
            steps {
                echo "Building.. ${env.BUILD_NUMBER}"
                sh("curl -u ${EXAMPLE_CREDS_USR}:${EXAMPLE_CREDS_PSW} https://example.com/")
                sh('curl -u $EXAMPLE_CREDS_USR:$EXAMPLE_CREDS_PSW https://example.com/')
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
