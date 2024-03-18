pipeline {
  agent any
  stages {
    stage("Clone Repo"){
      steps{
        sh 'git clone https://github.com/VijayKeerthan/c-project.git test-repo3'
      }
    }
    stage("Build project"){
      steps {
        sh 'gcc test.c -o app'
      }
    }
  }
}
