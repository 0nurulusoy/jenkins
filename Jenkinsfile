pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'docker pull hello-world:latest'
                sh 'docker tag hello-world:latest my-image:latest'
            }
        }
        stage('Run') {
            steps {
                sh 'docker run hello-world:latest'
            }
        }
    }
}
