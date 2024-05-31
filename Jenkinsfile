@Library('piper-lib-os')

node() {
  stage('init') {
    deleteDir()
    checkout scm
  }
  stage('deployIntegrationArtifact Command') {
       integrationArtifactDeploy script: this
  }
}
