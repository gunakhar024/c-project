pipeline {
  agent any
  stages {
    stage("Clone Repo"){
      steps{
        sh 'git clone https://github.com/VijayKeerthan/c-project.git test-repo2'
      }
    }
    stage("Build project"){
      steps {
        sh 'make all'
      }
    }
  }
}
