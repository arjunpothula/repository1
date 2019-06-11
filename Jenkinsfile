pipeline {
  agent {
    node {
      label 'master'
    }

  }
  stages {
    stage('Compile') {
      parallel {
        stage('Compile') {
          steps {
            sh 'mvn clean compile'
          }
        }
        stage('Archive') {
          steps {
            junit '*.tt'
          }
        }
      }
    }
  }
}