pipeline {
  agent any
  stages {
    stage('pipeline1') {
      steps {
        sh '''Jenkinsfile (Declarative Pipeline)
pipeline {
    agent { docker \'maven:3.3.3\' }
    stages {
        stage(\'build\') {
            steps {
                sh \'mvn --version\'
            }
        }
    }
}'''
      }
    }

    stage('') {
      steps {
        echo 'Hello world'
      }
    }

  }
}