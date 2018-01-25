pipeline {
  agent any
  stages {
    stage('Setup') {
      steps {
        echo 'Executing Setup Stage'
      }
    }
    stage('Build Image') {
      steps {
        echo 'Executing Build Image Stage'
        echo 'Executing Another Build Step'
      }
    }
    stage('Run Container') {
      steps {
        echo 'Executing Run Container Stage'
      }
    }
    stage('Test Container') {
      steps {
        echo 'Running Test Stage'
      }
    }
    stage('Push Image') {
      steps {
        echo 'Push Image To Docker DTR'
      }
    }
  }
}