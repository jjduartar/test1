pipeline {
  agent any
  stages {
    stage('Saludo') {
      steps {
        echo 'Hola desde Blue Ocean'
      }
    }

    stage('Development') {
      steps {
        sh 'env'
      }
    }

    stage('Exit') {
      steps {
        env 'Terminando proyecto'
      }
    }

  }
}


416916039139815