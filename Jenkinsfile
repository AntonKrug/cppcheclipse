pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        sh '''cd com.googlecode.cppcheclipse.parent
mvn clean verify
'''
      }
    }
  }
}