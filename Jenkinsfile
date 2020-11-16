pipeline {
  agent any
  stages {
    stage('GIT') {
      agent any
      steps {
        git(url: 'https://github.com/leelamanikanta/simpletomcat', branch: 'MASTER', changelog: true, poll: true, credentialsId: '5ea0c695-2056-4bde-ae3b-f3279a626675	')
      }
    }

  }
}