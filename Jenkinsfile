pipeline {
  agent any
  stages {
    stage('Test') {
      steps {
        timestamps() {
          echo 'Hello world'
        }

      }
    }
    stage('Build') {
      steps {
        timestamps() {
          echo 'Building'
          sh 'ps aux'
        }

      }
    }
  }
}