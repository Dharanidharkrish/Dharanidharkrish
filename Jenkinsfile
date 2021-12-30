pipeline
{
  agent
  {
    node
    {
      label 'Local'
    }
  }
  // testing payload
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
