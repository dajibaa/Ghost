pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        build(job: 'BuilProj', propagate: true)
      }
    }

  }
}