pipeline {
  agent any
  
  stages {
    stage('First') {
      steps {
        // checkout([$class: 'GitSCM', branches: [[name: '*/main']], extensions: [], userRemoteConfigs: [[url: 'https://github.com/yoav-klein/jenkins-test1.git']]])
        sh script: 'ls; exit 0'
      }
    }
  }
  
}
