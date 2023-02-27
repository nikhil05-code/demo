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
      }
      post {
        success {
          echo "Success"
        }
        faiure {
          echo "Failure"
        }
      }
    }
  }
}
