pipeline {
  agent any
  stages {
  stage('Maven install') {
    steps {
      withMaven(maven: 'maven3') {
      bat 'mvn clean install'
      }
    }
  }

}

}
