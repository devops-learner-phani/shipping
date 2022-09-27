pipeline {
  agent any
  options {
    ansiColor('xterm')
  }
  stages {
    stage('Compile package') {
      steps {
        sh 'mvn clean package'
      }
    }
  }
}