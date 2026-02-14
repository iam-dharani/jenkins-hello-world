pipeline {
  agent any
  tools {
    maven "3912"
  }
  stages {
    stage('mvn version') {
      steps {
        sh 'mvn -version'
      }
    }
  }
}
