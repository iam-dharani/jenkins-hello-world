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
   stage('build and package') {
     steps {
       sh 'mvn clean package -DskipTests=true'
     }
   }
   stage('test') {
     steps {
      sh 'mvn test'
    }
  }
 }
}
