pipeline {
  agent any
  stages {
    stage('local') {
      steps {
        bat(script: 'curl -H "Content-Type:application/json" -X POST -d "{\\"exePath\\":\\"E:\\\\TestFile\\\\PipelineTest\\\\LOCALService\\\\LOCALService.exe\\",\\"unityPath\\":\\"RTpcVW5pdHlcMjAxOC40LjMxZjFcRWRpdG9yXFVuaXR5LmV4ZQ==\\",\\"projectPath\\":\\"RTpcUFBUZXN0XEdvdF8yMDE4XEdvdF8yMDE4\\",\\"projectName\\":\\"Z2l0aHViXzAyMDY=\\",\\"type\\":\\"LOCALUPLOAD\\",\\"buildId\\":\\"%BUILD_ID%\\",\\"pipelineName\\":\\"Z2l0aHVi\\",\\"branchName\\":\\"bWFzdGVy\\",\\"computerType\\":\\"MQ==\\"}" http://localhost:9898', encoding: '', label: '', returnStatus: '', returnStdout: '')
      }
    }

  }
}