pipeline {
    agent none
    stages {
        stage('vcs') {
            steps { 
                sh 'git --version'
            }
        }
        stage('build') {
            steps {
                sh 'mvn --version'
        }
        stage('deploy') {
            steps {
                sh 'kubectl --version'
            }
        }
    }

}
