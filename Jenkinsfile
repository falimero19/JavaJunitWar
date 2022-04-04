pipeline {
  agent any
  stages {
    stage('prepare') {
      steps {
        sh 'echo "hello world"'
      }
    }

    stage('build') {
      steps {
        sh 'mvn clean install'
      }
    }

  }
}