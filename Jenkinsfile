pipeline {
  agent any
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
  environment {
    ENVIRONMENT = 'DEV'
  }
}