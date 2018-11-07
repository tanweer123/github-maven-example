pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        build(job: 'create a build', quietPeriod: 1)
      }
    }
    stage('test') {
      steps {
        isUnix()
      }
    }
  }
}