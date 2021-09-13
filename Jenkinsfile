pipeline {
    agent any
        docker { image 'node:14-alpine' }
    stages {
        stage('Build') {
            steps {
                sh node --version
            }
        }
        stage('Test') {
            steps {
                echo 'Test'
            }
        }
    }
}
