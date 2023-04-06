@Library('jenkins-poc-shared-lib') _

pipeline {
  agent any
  stages {
    stage('Hello World') {
      steps {
        helloWorld(name:"Carlos", projectName:"jenkins-poc-2")
        helloWorldSimple("Carlos","jenkins-poc-2")
        helloWorldExternal(name:"Carlos", projectName:"jenkins-poc-2")
      }
    }
  }
}
