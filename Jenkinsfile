pipeline {
    agent { docker { image 'nginx' } }
    stages {
        stage('build') {
            steps {
                sh 'echo hello'
            }
        }
    }
}
