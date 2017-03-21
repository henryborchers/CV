pipeline {
  agent none
  stages {
    stage('start') {
      agent any
      steps {
        parallel(
          "start": {
            echo 'hello world'
            echo 'Hello There'
            
          },
          "stage2": {
            echo 'asdfasdf'
            
          }
        )
      }
    }
    stage('sss') {
      steps {
        echo 'ssss'
      }
    }
  }
}