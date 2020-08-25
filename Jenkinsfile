pipeline {
  agent any
  stages {
    stage('code build') {
      steps {
        sh 'mvn package -f pom.xml'
      }
    }

  }
}
