pipeline {
  agent any
  triggers{
    pollscm('*/5 * * * *')
  }
    
  stages {
    stage('Checkout') {
    steps {
      echo "Récupération du code source from changes "
      checkout scm
      }
    }
stage('Build') {
steps {
echo "Build du projet"


}
}
stage('Deploy') {
steps {
echo "Déploiement du projet"
  }
}
}
}