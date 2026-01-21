pipeline {
    agent any
    environment {
        ENVIRONMENT = "${ENVIRONMENT}"
    }
    stages {
        stage('Build') {
            steps {
                echo "Building project for ${ENVIRONMENT} environment"
            }
        }
        stage('Test') {
            steps {
                echo "Running tests in ${ENVIRONMENT} environment"
            }
        }
    }
}
