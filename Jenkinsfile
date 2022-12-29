pipeline {
  agent any
  stages {
    stage('log tool version') {
      parallel {
        stage('log tool version') {
          steps {
            sh '''git --version
java --version 
mvn --version'''
          }
        }

        stage('check the pom') {
          steps {
            fileExists 'pom.xml'
          }
        }

      }
    }

  }
}