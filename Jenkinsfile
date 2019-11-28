pipeline {
  agent any
  stages {
    stage('DockerBuild') {
      steps {
        mail(subject: 'demarage du build', body: 'idem', from: 'admin@f80.fr', to: 'herve.hoareau@f80.fr')
      }
    }

  }
}