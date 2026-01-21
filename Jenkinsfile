pipeline {
    agent any
    environment {
        ENVIRONMENT = "DEV"   // set a default value here
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
