pipeline {
  agent any
  stages {
    stage("Clone Repo"){
      steps{
        sh 'rm -rf /var/lib/jenkins/workspace/pipeline-name/c-project'
        sh 'git clone https://github.com/VijayKeerthan/c-project.git'
      }
    }
    stage("Build project"){
      steps {
        sh 'gcc calculator.c -o app'
      }
    }
  }
}
