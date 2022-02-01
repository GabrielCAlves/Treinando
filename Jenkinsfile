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
        mail(body: 'Estamos iniciando a pipeline', subject: '[Jenkins] iniciando pipeline', replyTo: 'gabriel0603@alu.ufc.br', to: 'gabriel0603@alu.ufc.br')
      }
    }

  }
}