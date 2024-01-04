pipeline {
  agent {
    node {
      label 'dev'
    }

  }
  stages {
    stage('dev') {
      steps {
        sh 'go test ./...'
      }
    }

  }
}