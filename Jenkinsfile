pipeline {
  agent any
  tools {
    maven 'Apache maven 3.8.8' 
  }
  
  stages {
    stage ('Build') {
      steps {
        sh 'mvn clean package'
      }
    }
