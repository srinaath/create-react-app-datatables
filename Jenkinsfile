pipeline {
  agent {
    dockerfile {
      filename 'JenkinsDockerFIle'
    }
    
  }
  stages {
    stage('Test') {
      steps {
        sh '''npm start
'''
      }
    }
  }
}