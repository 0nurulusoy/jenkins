pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'docker pull tryingtobecoder/docker-hello-world:latest'
                sh 'docker tag tryingtobecoder/docker-hello-world:latest my-image:latest'
            }
        }
        stage('Run') {
            steps {
                sh 'docker run my-image:latest'
            }
        }
    }
}
