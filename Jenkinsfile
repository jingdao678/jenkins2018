node {
    try{
        stage('Test') {
            sh './gradlew check'
        }
    finally {
        junit 'build/reports/**/*.xml'
    }
}
