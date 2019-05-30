pipeline {
  agent any
  stages {
    stage('bulid') {
      agent any
      steps {
        sh 'mvn -B -DskipTests clean package'
      }
    }
  }
}