pipeline {
    agent { 
        docker { 
            image 'tisho1313/primer1:latest'
            args '-p 3000:3000'
            registryUrl 'https://docker.com/'
            registryCredentialsId 'dcbd9acd-3236-4c3a-aebc-1a77a20d513b'
        } 
    }
    stages {
        stage('Build') {
            steps {
                sh 'node --version'
                sh 'echo "Stage Build"'
                sh 'mkdir -p output'
            }
        }
        stage ('Deliver') {
            steps {
                sh 'echo "Batura Matura "'
            }
        }
    }
}
