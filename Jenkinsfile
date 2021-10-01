pipeline {
    agent { docker { image 'golang' } }
    stages {
        stage('build') {
            steps {
                sh 'go version'
                sh 'echo build'
            }
        }
        stage('deploy') {
            steps {
                sh 'echo deploy'
            }
        }
    }
}