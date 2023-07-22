pipeline {
  agent any
  stages {
    stage('Pull image') {
      steps {
        sh 'docker run -p 8080:8080 sonnnguyen1129/new-jenkins'
      }
    }

  }
}