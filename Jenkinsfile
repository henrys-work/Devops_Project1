pipeline {
    agent any
    stages {
        stage('build docker image') {
            steps {
                sh 'echo Building Docker image'
            }
        }
        stage('Run docker Container') {
            steps {
		sh 'echo running docker container' 
              }
        }
        stage('test') {
            steps {
                sh 'echo test'
            }
        }
    }
}
