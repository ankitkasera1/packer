pipeline{
agent any
stages {
    stage('Build') {
      steps {
        sh 'cd $GOPATH/src/github.com/hashicorp/packer'
        sh 'go get'
        sh 'make'
      }
    }
}
