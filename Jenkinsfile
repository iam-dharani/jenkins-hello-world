pipeline {
  agent any
  tools {
    mvn '3912'
  }
  stages {
    stage('mvn version') {
      steps {
        sh 'mvn -version'
      }
    }
  }
}
