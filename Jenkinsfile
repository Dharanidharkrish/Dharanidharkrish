pipeline
{
  agent
  {
    node
    {
      label 'Local'
    }
  }
  // testing payloads
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
