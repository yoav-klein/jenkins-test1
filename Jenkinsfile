/*pipeline {
  agent any
  
  stages {
    stage('First') {
      steps {
        sh script: 'ls; env;exit 0'
      }
    }
  }
  
}*/

// checkout([$class: 'GitSCM', branches: [[name: '*/main']], extensions: [], userRemoteConfigs: [[url: 'https://github.com/yoav-klein/jenkins-test1.git']]])

println("HERE")
node {
  sh script: "ls"
  sh script: "env"
  if(env.BRANCH_NAME == "main") {
    println "MASTER!!!!"
  }
}
