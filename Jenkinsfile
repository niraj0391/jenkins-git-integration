pipeline {
  agent any
  stages {
    stage('code build') {
      steps {
        bat 'mvn package -f pom.xml'
      }
    }

  }
}
