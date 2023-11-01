default:
  agentLabel = "master"
  break
}
pipeline {
  agent {
    label "${agentLabel}"
  }
  options {
    skipDefaultCheckout(true)
  }
 stage('Code Checkout') {
      steps {
        script {
          checkout scm
        }
      }
    }
