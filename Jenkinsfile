pipeline {
  agent any
  stages {
    stage("Clone Repo"){
      steps{
        sh 'git clone https://github.com/VijayKeerthan/c-project.git test-repo1'
      }
    }
    stage("Build project"){
      steps {
        sh 'make'
      }
    }
  }
}
