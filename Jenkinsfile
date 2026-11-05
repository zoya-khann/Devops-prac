pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        bat 'echo "Compiling"'
      }
    }

    stage('Test') {
      steps {
        bat 'echo "Running test"'
      }
    }

    stage('Deploy') {
      steps {
        bat 'echo "Deploying application"'
      }
    }

    stage('End') {
      steps {
        bat 'echo "Pipeline completed successfully"'
      }
    }

  }
}