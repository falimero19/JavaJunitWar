pipeline {
  agent any
  stages {
    stage('prepare') {
      steps {
        git(url: 'git@github.com:falimero19/JavaJunitWar2.git', branch: '/*main')
        sh 'echo "hello world"'
      }
    }

  }
}