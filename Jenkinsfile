pipeline{
   agent any

   environment{
   PATH = /opt/mvn3/bin:$PATH
   }
   stages{
     stage('checkout') {
      steps{
      git cridentialId: 'github' url: 'https://github.com/gopal4/hello-world.git'
      }
     }
     stage('build') {
      steps{
      sh 'mvn clean install'
      }
     }
   }
}
