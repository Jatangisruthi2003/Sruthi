pipeline
{
  agent any
  stages
    {
    stage('clone')
    {
      steps
      {
        git 'https://github.com/Jatangisruthi2003/Sruthi.git'
      }
    }
    stage('Build')
    {
      steps
      {
        sh 'javac HelloWorld.java'
      }
    }
    stage('RUN')
    {
      steps
      {
        sh 'java HelloWorld'
      }
    }
  }
}

