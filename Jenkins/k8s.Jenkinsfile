pipeline {
    agent { 
        node {
            label 'built-in'
            }
      }
    stages {
        stage('Build') {
            steps {
                echo "Building.."
                sh '''
                echo "doing build k8s stuff.."
                '''
            }
        }
        stage('Test') {
            steps {
                echo "Testing.."
                sh '''
                echo "doing test k8s stuff.."
                '''
            }
        }
        stage('Deliver') {
            steps {
                echo "Deliver...."
                sh '''
                echo "doing delivery k8s stuff.."
                '''
            }
        }
    }
}