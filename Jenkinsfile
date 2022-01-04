parameters {
        string(defaultValue: "123", description: 'This is a parameter', name: 'PARAMETER01')}
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
          println(payload)
        }
      }
    }
  }
}
