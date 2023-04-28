pipeline{

  any agnet
  environment{
    VERSION = "${env.BUILD_ID}"
  }
  stages{
    stage('Code clone'){
      git branch: 'master' url:'https://github.com/Suresh-the1/javasample.git'
    }
  }
}
