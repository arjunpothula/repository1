pipeline {
  agent {
    node {
      label 'JAVA'
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
