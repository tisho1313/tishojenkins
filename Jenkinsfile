pipeline {
    agent { 
        docker { 
            image 'tisho1313/primer1:latest'
            args '-p 3000:3000'
            registryUrl 'https://hub.docker.com/'
            registryCredentialsId '4415c874-654d-42cb-a3d9-977ceb185e55'
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
