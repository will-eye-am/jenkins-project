pipeline {
    agent { docker { image '3.11-rc-bullseye' } }
    stages {
        stage('build') {
            steps {
                sh 'python --version'
            }
        }
    }
}