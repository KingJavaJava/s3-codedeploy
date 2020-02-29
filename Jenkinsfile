pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        s3Upload 'cicd-group'
      }
    }

  }
}