pipeline {
  agent any
  stages {
    stage("Clone Repo"){
      steps{
        sh 'rm -rf /var/lib/jenkins/workspace/calculater/c-project'
        sh 'git clone https://github.com/gunakhar024/c-project.git'
      }
    }
    stage("Build project"){
      steps {
        sh 'gcc calculator.c -o app'
      }
    }
  }
}
