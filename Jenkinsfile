pipeline{

  any agnet
  environment{
    VERSION = "${env.BUILD_ID}"
  }
  stages{
    stage('Code clone'){
      scripts{
      git branch: 'master', url:'https://github.com/Suresh-the1/javasample.git'
      }
    }
  }
}
