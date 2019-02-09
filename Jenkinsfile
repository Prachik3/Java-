pipeline {
  agent any
  stages {
    stage('stage') {
      steps {
        sh 'echo "Hell World"'
      }
    }
    stage('Build') {
      steps {
        git(url: 'https://github.com/Prachik3/Java-.git', branch: 'Test', changelog: true, credentialsId: 'test', poll: true)
      }
    }
  }
}