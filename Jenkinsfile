pipeline {
  agent any
  stages {
    stage('Start') {
      parallel {
        stage('Start') {
          steps {
            echo 'First Stage Test'
          }
        }
        stage('Stage 2') {
          steps {
            echo 'test stage 2'
          }
        }
      }
    }
  }
}