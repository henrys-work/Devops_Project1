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
        sh 'docker run  -p 5000:5000 devops_project_docker_image'
      }
    }
    stage('test') {
      steps {
        sh 'echo test'
      }
    }
  }
}
