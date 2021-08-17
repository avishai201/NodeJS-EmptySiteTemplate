pipeline {
  agent any
  stages {
    stage('Check Out Code ') {
      steps {
        git(url: 'https://github.com/avishai201/NodeJS-EmptySiteTemplate.git', branch: 'master', changelog: true, poll: true)
      }
    }

  }
}