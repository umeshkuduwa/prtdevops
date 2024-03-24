pipeline {
    agent any
    
    stages {
        stage('Build Docker Image') {
            steps {
                script {
                    // Build Docker image using Dockerfile
                    docker.build('umeshkuduwa/prtdockerimg:latest')
                }
            }
        }
    }
}
