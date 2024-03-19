pipeline {
  agent any
  stages {
    stage("Clone Repo"){
      steps{
        sh 'git clone https://github.com/VijayKeerthan/c-project.git'
        sh 'rm -rf /var/lib/jenkins/workspace/test/c-project/.git'
      }
    }
    stage("Build project"){
      steps {
        sh 'gcc test.c -o app'
      }
    }
  }
}
