pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        echo 'build completed succesfully'
        timeout(time: 5, unit: 'NANOSECONDS') {
          sh 'sleep 10'
      }
      }
    }

   stage('Test') {
      steps {
        echo 'testing completed succesfully'
      }
    }

    stage('deploy') {
      steps {
        echo 'deploy completed succesfully'
      }
    }

  }
}