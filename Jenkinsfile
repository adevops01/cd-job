pipeline {

  agent any

  stages {

    stage('Deploy to Kubernetes') {

      steps {
        
        sh 'kubectl apply -f manifests/'

      }

    }

  }

}
