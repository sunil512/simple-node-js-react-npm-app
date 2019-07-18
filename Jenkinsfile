pipeline {
  agent {
    docker {
      args '-p 3000:3000'
      image '4c108a37151f'
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