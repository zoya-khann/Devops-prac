pipeline {
  agent any
  stages {
    stage('Build') {
      parallel {
        stage('Build') {
          steps {
            bat 'echo "Compiling"'
          }
        }

        stage('Build Stage') {
          steps {
            bat 'echo "Build Version 1.0" > build-info.txt'
          }
        }

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