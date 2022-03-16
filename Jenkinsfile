pipeline {
  agent any
  stages {
    stage('CD') {
      steps {
        azureWebAppPublish(appName: 'sample-web-application-01', resourceGroup: 'BlueOcean', azureCredentialsId: '/subscriptions/32b57df5-5519-46b0-ab78-9b78e94fd4c8/resourceGroups/BlueOcean')
      }
    }

  }
}