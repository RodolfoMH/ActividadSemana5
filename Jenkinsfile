pipeline {
  agent {
    docker {
      image 'node:12'
      args '--network actividad_mynet'
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