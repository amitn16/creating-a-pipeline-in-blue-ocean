pipeline {
  agent any
  stages {
    stage('a') {
      agent {
        docker {
          image 'node:6-alpine'
        }

      }
      steps {
        build 'a'
      }
    }

  }
}