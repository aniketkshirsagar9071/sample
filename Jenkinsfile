pipeline {
  agent any
  stages {
    stage('test') {
      steps {
        sh 'mvn --version'
      }
    }

    stage('build') {
      steps {
        sh '''ls 
date
cal 2021'''
      }
    }

  }
}