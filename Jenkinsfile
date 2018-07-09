pipeline {
  agent {
    docker {
      args '-p 3000:3000'
      image 'node:10.6.0-slim'
    }

  }
  stages {
    stage('Build') {
      steps {
        sh 'npm install'
      }
    }
  }
}