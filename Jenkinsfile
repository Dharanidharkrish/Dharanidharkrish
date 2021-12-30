pipeline
{
  agent
  {
    node
    {
      label 'Local'
    }
  }
  environment
  {
      GIT_URL = "${GIT_URL }"
  }
  // testing
  stages
  {
    stage('TEST')
    {
      steps
      {
        script
        {
          println(GIT_URL)
        }
      }
    }
  }
}
