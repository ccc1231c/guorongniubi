pipeline {
  agent any
  stages {
    stage('11') {
      steps {
        echo '111222'
        bat(script: '''echo 111
echo 222''', encoding: null, label: null, returnStatus: false, returnStdout: false)
      }
    }

    stage('s') {
      steps {
        sleep(time: 10, unit: 'SECONDS')
      }
    }

    stage('222') {
      steps {
        echo '222'
      }
    }

  }
}