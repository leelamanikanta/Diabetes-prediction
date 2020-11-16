pipeline {
  agent any
  stages {
    stage('GIT') {
      agent any
      steps {
        git(url: 'https://github.com/leelamanikanta/simpletomcat', changelog: true, poll: true, credentialsId: 'b9a3eb70-d3a4-4f66-a685-9596f6f3cb19')
      }
    }

  }
}