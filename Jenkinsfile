pipeline {
  agent {
    node {
      label 'ssh-node'
    }

  }
  stages {
    stage('Build') {
      steps {
        sh 'echo "this is build"'
      }
    }

    stage('test') {
      steps {
        sh 'echo "this is test"'
      }
    }

    stage('deploy') {
      steps {
        echo 'deployed successfully'
      }
    }

  }
}