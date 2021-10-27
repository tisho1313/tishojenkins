pipeline {
    agent { 
        docker { 
            image 'tisho1313/primer1:latest'
            args '-p 3000:3000'
            registryUrl 'https://docker.com/'
            registryCredentialsId '3b1ec055-2d12-4aa9-b7dc-7468b75bc90d'
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
