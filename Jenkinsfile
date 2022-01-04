parameters {
        string(defaultValue: "", description: 'This is a payload parameter', name: 'payload')}
//adding comment for testing
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
