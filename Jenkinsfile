pipeline {
  agent any
  stages {
    stage("Clone Repo"){
      steps{
        sh 'git clone https://github.com/VijayKeerthan/c-project.git test-repo'
      }
    }
    stage("Build project"){
      steps {
        sh 'make'
      }
    }
  }
}
