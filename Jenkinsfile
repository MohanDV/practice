pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        sh 'cat README.md'
      }
    }

    stage('test') {
      steps {
        sh 'cat untracked.txt'
      }
    }

  }
}