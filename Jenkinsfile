pipeline {
  agent any
  stages {
    stage('prepare') {
      steps {
        git(url: 'https://github.com/falimero19/JavaJunitWar2.git', branch: '/*main')
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