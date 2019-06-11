pipeline {
  agent {
    node {
      label 'master'
    }

  }
  stages {
    stage('Compile') {
      steps {
        sh "mvn clean compile"
      }
    }
  }
}
