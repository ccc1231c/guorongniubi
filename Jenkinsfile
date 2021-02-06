pipeline {
  agent {
    node {
      label 'mac1'
    }

  }
  stages {
    stage('local') {
      steps {
        sh(script: '"mono" "/Users/uwa4d/Desktop/PipelineTest/LOCALService/LOCALService.exe" "LOCALUPLOAD" "L0FwcGxpY2F0aW9ucy9Vbml0eTIwMTcuNC4zL1VuaXR5LmFwcC9Db250ZW50cy9NYWNPUy9Vbml0eQ==" "L1VzZXJzL3V3YTRkL0Rlc2t0b3AvdGVzdF8wMTA2" "${BUILD_ID}" "Z2l0aHViX2xpbnV4XzAyMDY=" "bWFzdGVy" "bWFjX2dpdGh1Yl9sb2NhbF8wMjA2" "Mg=="', encoding: '', label: '', returnStatus: '', returnStdout: '')
      }
    }

  }
  environment {
    PATH = '/Library/Frameworks/Python.framework/Versions/3.7/bin:/usr/local/bin:/usr/bin:/bin:/usr/sbin:/sbin:/Library/Frameworks/Mono.framework/Versions/Current/Commands'
  }
}