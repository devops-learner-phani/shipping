pipeline {
  agent any
  stages {
    stage('Compile package') {
      steps {
        sh 'mvn clean package'
      }
    }
  }
}