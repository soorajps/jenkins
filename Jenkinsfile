pipeline {
    agent { docker { image 'node' } }
    stages {
        stage('build') {
            steps {
                sh 'node --version'
            }
        }
    }
}