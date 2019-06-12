Jenkinsfile (Declarative Pipeline)
pipeline {
    agent { docker 'Python:2.7.5' }
    stages {
        stage('build') {
            steps {
                sh 'python --version'
            }
        }
    }
}
