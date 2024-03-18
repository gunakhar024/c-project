pipeline {
  agent any
  stages {
    stage("Clone Repo"){
      steps{
        sh 'git clone https://github.com/VijayKeerthan/c-project.git'
      }
    }
    stage("Build project"){
      steps {
        sh 'make'
      }
    }
  }
}
