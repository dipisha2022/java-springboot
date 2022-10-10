pipeline {
  agent any

  stages {
    stage('Build') {
        steps {
            echo 'Build'
        }
    }
    stage('Test') {
        steps {
            echo 'Test'
        }

    }
    stage('Sonarqube') {
        steps {
            echo 'Sonarqube'
        }

    }
    stage('Push to artifactory') {
        steps {
            echo 'Push to artifactory'
        }

    }
    stage('Deploy to QA') {
        steps {
            echo 'Deploy to QA'
        }
    }
    stage('Deploy to Prod') {
        echo 'Deploy to Prod'
    }
  }
  post {
    always {
        echo 'I will always say Hello again'
    }
  }
}


