pipeline {
  agent {
    docker { image 'node:7-alpine' }
  }
  stages {
    stage('Build') {
      steps {
        sh 'npm install'
        sh 'npm run build'
      }
    }
  }
}
