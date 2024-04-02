pipeline {
  agent{
    node{
      label 'ssh-node'
      customWorkspace '/home/jenkins/jenkins-agent/customWorkspace'
    }
  }
  options {
    skipDefaultCheckout()
  }
  stages {
    stage('Build') {
      agent{
        node{
          label 'ssh-node'
          customWorkspace '/home/jenkins/jenkins-agent/customWorkspace'
        }
      }
      // agent any
      options {
        skipDefaultCheckout()
      }
      steps {
        echo "this is build"
      }
    }
  }
}