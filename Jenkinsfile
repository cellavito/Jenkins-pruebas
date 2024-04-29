pipeline {
        agent { label 'docker-agent-jdk17' }
    stages {
        stage('build') {
            steps {
                sh 'mvn --version'
            }
        }
    }
}
