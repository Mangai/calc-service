pipeline {
  agent any
  stages {
    stage('Code') {
      steps {
        git(url: 'https://github.com/mypractice96/calc-service', branch: 'master')
      }
    }
    stage('Build') {
      steps {
        sh 'echo "Build here"'
      }
    }
    stage('Deploy') {
      steps {
        sh 'echo "Deploy here"'
      }
    }
  }
}