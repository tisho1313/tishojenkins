pipeline {
    agent { 
        docker { 
            image 'tisho1313/primer1:latest'
            args '-p 3000:3000'
            registryUrl 'https://hub.docker.com/repository/docker/tisho1313/primer1'
            registryCredentialsId 'e6c539d2-df28-49ec-9e72-9a2cbd55ac4e'
        } 
    }
    stages {
        stage('Build') {
            steps {
                sh 'node --version'
                sh 'echo "Stage Build"'
            }
        }
        stage ('Deliver') {
            steps {
                sh 'echo "Batura Matura "'
            }
        }
    }
}
