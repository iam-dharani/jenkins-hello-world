pipeline {
  agent any
  tools {
    maven 'mvn 3912'
  }
  stages {
    stage('mvn version') {
      steps {
        sh 'mvn -version'
      }
    }
  }
}
