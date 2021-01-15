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

  }
}