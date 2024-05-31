@Library('piper-lib-os') _

node() {
  stage('init') {
    deleteDir()
    checkout scm
  }
  stage('deploy') {
       integrationArtifactDeploy script: this
  }
}
