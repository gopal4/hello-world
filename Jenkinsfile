pipeline{
    agent any
    stages{
      stage('git checkout'){
         steps{
           git credentialsId: 'github', url: 'https://github.com/gopal4/hello-world.git'
         }
      }
    }
}
