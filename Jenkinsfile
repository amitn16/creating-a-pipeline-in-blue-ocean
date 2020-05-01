pipeline {
  agent any
  stages {
    stage('a') {
      agent {
        docker {
          image 'node:6-alpine'
          args '-p 3000:3000'
        }

      }
      steps {
        build 'a'
      }
    }

  }
}