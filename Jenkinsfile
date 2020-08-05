pipeline{
   agent any

   environment{
   PATH = /opt/mvn5/bin:$PATH
   }
   stages{
     stage('checkout firt stage') {
      steps{
      git url: 'https://github.com/gopal4/hello-world.git'
      }
     }
     stage('build second stage') {
      steps{
      sh 'mvn clean install'
      }
     }
   }
}
