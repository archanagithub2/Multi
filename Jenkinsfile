pipeline{
  agent any
  stages{
    stage('Print Java')
    {
      steps{
        sh 'java -version'
      }
    }
    stage('cat README')
    {
      steps
      {
        sh 'cat README.md'
      }
    }
        stage('Printing Hello')
    {
      steps
      {
        echo 'hello'
      }
    }
        stage('Greeting')
    {
      steps
      {
        echo 'Hello'
      }
    }
  }
}
