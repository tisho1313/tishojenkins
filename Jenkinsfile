pipeline {
    agent { 
        docker { 
            image 'tisho1313/primer1:latest'
            args '-p 3000:3000'
            registryUrl 'https://docker.com/'
            registryCredentialsId '57431c91-be0f-4023-a9ad-947a1e48da2a'
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
