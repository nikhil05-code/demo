pipeline {
  agent none
  environment {
    EXECUTEBUILD = true
  }
  stages {
    stage('Build') {
      agent {
        docker {
          image 'node:18'
        }
      }
      steps {
        echo "Node image"
        sh 'node --version'
      }
    }
  }
}
