pipeline {
  agent any
  stages {
    stage('check code') {
      steps {
        git(url: 'https://github.com/pmmridul/mysite.git', branch: 'master')
      }
    }

    stage('List') {
      steps {
        sh 'ls -la'
      }
    }

  }
}