node {
    stage('Build and run') {
        docker.image('alpine:latest').inside {
            sh 'echo "Hello World"'
        }
    }
}
