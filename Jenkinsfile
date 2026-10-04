pipeline {
    agent any

    stages {
        stage('Check Jenkins') {
            steps {
                sh 'echo "Jenkins is working"'
                sh 'whoami'
                sh 'hostname'
            }
        }

        stage('Check Kubernetes') {
            steps {
                sh 'kubectl get nodes'
            }
        }
    }
}
