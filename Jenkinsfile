pipeline {
  agent any
  stages {
    stage('Local') {
      steps {
        bat(script: 'curl -H "Content-Type:application/json" -X POST -d "{\\"exePath\\":\\"E:\\\\TestFile\\\\Commercial\\\\local\\\\LOCALService.exe\\",\\"unityPath\\":\\"RTpcVW5pdHlcMjAxOC40LjMxZjFcRWRpdG9yXFVuaXR5LmV4ZQ==\\",\\"projectPath\\":\\"RTpcUFBUZXN0XEdvdF8yMDE4XEdvdF8yMDE4\\",\\"projectName\\":\\"R2l0aHViX3dpbmRvd3NfMDIwNw==\\",\\"type\\":\\"LOCALUPLOAD\\",\\"buildId\\":\\"%BUILD_ID%\\",\\"pipelineName\\":\\"R2l0aHViXzAyMDc=\\",\\"branchName\\":\\"bWFzdGVy\\",\\"computerType\\":\\"MQ==\\"}" http://localhost:9898', encoding: '', label: '', returnStatus: '', returnStdout: '')
      }
    }

  }
}