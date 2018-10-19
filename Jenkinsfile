pipeline {
  agent any
  stages {
    stage('Ingreso al directorio web') {
      steps {
        sh 'cd /var/www/vhosts/demo'
        git(url: 'https://github.com/andreani-operaciones/startup-index.git', poll: true)
      }
    }
  }
}