pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh '''mix deps.get
mix compile
mix test'''
      }
    }
  }
}