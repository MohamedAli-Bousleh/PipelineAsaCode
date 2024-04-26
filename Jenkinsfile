pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        echo 'build comleted succesfully'
        timeout(time: 5, unit: 'NANOSECONDS') {
          sh 'sleep 10'
      }
      }
    }

   stage('Test') {
      steps {
        echo 'testing comleted succesfully'
      }
    }

  }
}