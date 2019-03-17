pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                sh 'echo "Hello from jenkins"'
                sh 'ls -l'
                sh 'go version'
            }
        }
        stage('Test') {
            steps {
                sh 'echo "bla bla!";'
            }
        }
    }
}