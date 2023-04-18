@Library('github.com/devbyaccident/demo-shared-pipeline') _

pipeline {
  agent any
  stages {
    stage('Verify Branch') {
      steps {
        echo $GIT_BRANCH
      }
    }
  }
}