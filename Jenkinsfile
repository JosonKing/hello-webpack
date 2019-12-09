Jenkinsfile (Declarative Pipeline)
pipeline {
    agent { docker 'node:12.13.0' }
    stages {
        stage('build') {
            steps {
                sh 'npm --version'
            }
        }
    }
}