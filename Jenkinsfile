pipeline {
  agent any
  stages {
    stage('build docker image') {
      steps {
        sh 'docker build -t devops_project_docker_image .'
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
