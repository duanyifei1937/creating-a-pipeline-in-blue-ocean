pipeline {
  agent {
    docker {
      args '-p 3000:3000'
      image 'harbor.qyvideo.net/fe/node:8.11.0-alpine'
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