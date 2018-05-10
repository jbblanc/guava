pipeline {
  agent {
    node {
      label 'local-agent'
    }

  }
  stages {
    stage('Build') {
      steps {
        sh 'mvn -B clean verify'
      }
    }
  }
  environment {
    myVar = 'myValue'
  }
}