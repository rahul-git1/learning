pipeline {
  agent any
  stages {
    stage('Stage 1') {
      parallel {
        stage('Stage 1') {
          steps {
            echo 'Hello Rahul'
          }
        }
        stage('stage2') {
          steps {
            echo 'Hello Stege2'
          }
        }
        stage('stage3') {
          steps {
            sh 'ls -l'
          }
        }
      }
    }
  }
}