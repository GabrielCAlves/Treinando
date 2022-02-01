pipeline {
  agent any
  stages {
    stage('Iniciando') {
      steps {
        echo 'Abrindo arquivo'
      }
    }

    stage('Enviando e Finalizando') {
      steps {
        mail(body: 'Estamos iniciando a pipeline', subject: '[Jenkins] iniciando pipeline')
      }
    }

  }
}