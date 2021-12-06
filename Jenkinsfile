pipeline {
  agent any
  stages {
    stage('error') {
      steps {
        echo 'testing'
      }
    }

  }
  environment {
    ECR_ID = '142198642907.dkr.ecr.ap-south-1.amazonaws.com'
    CALCULATION_SERVICE_IMAGE = '\'manojv2-casestudy-calculation-service\''
    ECR_CREDENTIALS = 'credentials(\'ecr-credentials\')'
  }
}