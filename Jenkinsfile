pipeline{

  agent any
  environment{
    VERSION = "${env.BUILD_ID}"
  }
  stages{
    stage('Code clone'){
      steps{
           script{
              git branch: 'master', url:'https://github.com/Suresh-the1/javasample.git'
           }
      }
    }
      stage('Build')
      {
        steps{
          script{
            sh 'mvn clean install'
          }
        }
     }
  }
}
