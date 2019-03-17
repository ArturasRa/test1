pipeline {
    agent { docker { image 'golang' } }
    stages {
        stage('build') {
            steps {
                sh 'echo "Hello from jenkins"'
                sh 'ls -l'
                sh 'go version'
            }
        }
    }
}