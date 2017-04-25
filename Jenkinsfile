pipeline {
  agent any
  stages {
    stage('echo') {
      steps {
        parallel(
          "echo": {
            sleep(time: 10, unit: 'SECONDS')
            
          },
          "echo fenzhi": {
            sh 'echo "fen ahi 2"'
            
          }
        )
      }
    }
    stage('echo1') {
      steps {
        sh 'echo "anbowei test"'
      }
    }
  }
}