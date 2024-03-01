pipeline {
  agent any
  stages {
    stage('activity 2') {
      steps {
        sh 'scripts/build.sh'
      }
    }

    stage('activity 3') {
      steps {
        sh 'script scripts/test.sh'
      }
    }

  }
  environment {
    registry = 'chris703/cicd_jenkins'
  }
}