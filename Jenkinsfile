pipeline {
    agent {
        label 'docker'
    }
    stages {
        stage('Test') {
            agent {
                docker {
                    steps {
                        sh 'node --version'
                    }
                }
            }
        }
    }
}
