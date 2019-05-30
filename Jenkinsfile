pipeline {
  agent any
  stages {
    stage('bulid') {
      agent any
      steps {
        sh 'mvn -B -DskipTests clean package'
      }
    }
    stage('test') {
      steps {
        sh 'echo "Fail!"'
      }
    }
    stage('post') {
      steps {
        echo 'This will always run'
      }
    }
  }
}
