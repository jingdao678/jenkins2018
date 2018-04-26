pipeline {
    agent {
        docker { image 'node:12f14589c77e' }
    }
    stages {
        stage('Test') {
            steps {
                sh 'node --version'
            }
        }
    }
}
