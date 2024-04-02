pipeline {
  agent none
  stages {
    stage('Build') {
      agent{
        node{
          label 'ssh-node'
          customWorkspace '/home/jenkins/jenkins-agent/customWorkspace'
        }
      }
      options {
        skipDefaultCheckout()
      }
      steps {
        echo "this is build"
      }
    }
  }
}