pipeline {
  agent any
  stages {
    stage("Clone Repo"){
      steps{
        sh 'sudo rm -rf .git'
        sh 'git clone https://github.com/VijayKeerthan/c-project.git'
      }
    }
    stage("Build project"){
      steps {
        sh 'gcc test.c -o app'
      }
    }
  }
}
