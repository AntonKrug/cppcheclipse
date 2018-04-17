pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        sh '''cd com.googlecode.cppcheclipse.parent
/opt/bin/mvn clean verify
'''
      }
    }
  }
}