pipeline {
  agent {
    docker {
      image 'node:12'
      args '--network jenkins-blue-ocean-tutorial_mynet'
    }

  }
  stages {
    stage('Build') {
      steps {
        echo 'Hola Mundo'
      }
    }

  }
}