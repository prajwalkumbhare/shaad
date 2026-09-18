pipeline {
 agent any
 environment {
    PATH = "/opt/maven/bin:$PATH"
 }
 stages {
  stage('hghgh') {
    steps {
       git url: 'https://github.com/prajwalkumbhare/shaad.git', branch: 'main'
          }
        }

   stage('ioioi') {
     steps {
       sh 'mvn clean package'
      }
    }
  }
}
