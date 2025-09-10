// Jenkinsfile simple (déclaratif)
pipeline {
  agent any

  stages {
    stage('Checkout') {
      steps {
        // Récupère le code depuis le SCM configuré dans Jenkins
        checkout scm
      }
    }

    stage('Build') {
      steps {
        // Remplacez par vos commandes de build
        sh 'echo "Build du projet"'
        sh 'mvn clean install'
      }
    }

    stage('Test') {
      steps {
        // Remplacez par vos tests (ex: mvn test, npm test, etc.)
        sh 'echo "Exécution des tests"'
      }
    }
  }

  post {
    always {
      // Actions post-pipeline (logs, nettoyage, etc.)
      echo 'Pipeline terminé.'
    }
  }
}
