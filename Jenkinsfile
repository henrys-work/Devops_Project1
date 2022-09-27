pipeline {
    agent { docker { image 'python:3.6.8' } }
    stages {
        stage('build') {
            steps {
                sh 'sudo -H pip install flask'
            }
        }
        stage('test') {
            steps {
                sh 'python test.py'
            }
        }
    }
}
