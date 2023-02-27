pipeline {
  agent none
  environment {
    EXECUTEBUILD = true
  }
  stages {
    stage('Build') {
      steps {
        echo "Node image"
      }
      post {
        success {
          echo "Success"
        }
      }
    }
  }
}
