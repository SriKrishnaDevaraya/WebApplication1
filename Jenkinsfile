pipeline {
  agent any
  stages {
    stage('CD') {
      steps {
        azureWebAppPublish(appName: 'sample-web-application-01', resourceGroup: 'BlueOcean', azureCredentialsId: '160e6f2f-dd4a-469a-bae9-a0fa3d45e291')
      }
    }

  }
}