pipeline {
    agent {
        docker { image 'alpine' }
    }
    stages {
        stage('Test') {
            steps {
                sh 'ubuntu --version'
            }
        }
    }
}
