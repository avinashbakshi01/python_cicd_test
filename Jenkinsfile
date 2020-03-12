pipeline {
  agent any
  stages {
    stage('***************') {
      steps {
        sh '''curl --location --request POST \'http://demo.strobes.co:8006/v1/sast_scan/bandit/config/208/start/8965d910-6fbf-4f19-ae41-a63f127264c5/\' \\
--header \'Authorization: token c09868996b806b5348cc96e4a0f1a03b3dc2cb93\''''
      }
    }

  }
}