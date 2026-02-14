pipeline {
  agent any
  tools {
    maven "mvn3912"
  }
  stages {
    stage('mvn version') {
      steps {
        sh 'mvn -version'
      }
    }
  }
}
