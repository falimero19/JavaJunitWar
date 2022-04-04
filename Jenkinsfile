pipeline {
  agent any
  stages {
    stage('prepare') {
      steps {
        sh 'echo "hello world"'
        git(branch: 'main', url: 'https://github.com/falimero19/JavaJunitWar2.git')
      }
    }

    stage('build') {
      steps {
        sh 'mvn clean install'
      }
    }

    stage('test') {
      steps {
        junit 'target/surefire-reports/TEST-*.xml'
      }
    }

  }
}