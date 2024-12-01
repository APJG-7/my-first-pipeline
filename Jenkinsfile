pipeline {
    agent any

    stages {
        stage("Build") {
            agent {
                docker { image 'node:latest' }
            }
            steps {
                script {
                    sh 'node --version'
                }
            }
        }
    }
}
