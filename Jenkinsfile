pipeline {
    agent { 
        docker { 
            image 'node:12.16.2'
            args '-p 3000:3000'
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
