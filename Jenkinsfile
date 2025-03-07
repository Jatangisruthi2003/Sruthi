pipeline
{
  agent any
  {
    stages
    {
    stage('clone')
    {
      steps
      {
        git''
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
