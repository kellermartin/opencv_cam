pipeline {
  agent { dockerfile true }
  stages {
    stage('Test') {
      steps {
        sh '''
          uname 
          uname -r
          ros2 --help
        '''
      }
    }
  }
}
