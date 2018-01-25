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
  }
}