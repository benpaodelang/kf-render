pipeline {
  agent any
  stages {
    stage('step2') {
      steps {
        parallel(
          "step2": {
            echo 'jejee'
            sleep 30
            
          },
          "hehe": {
            echo 'caodan'
            
          }
        )
      }
    }
    stage('step4') {
      steps {
        echo 'caodan'
      }
    }
  }
}