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
          println(GIT_COMMIT)
          println(GIT_AUTHOR_NAME)
          println(GIT_URL_N)
          println(GIT_BRANCH)
          println(GIT_LOCAL_BRANCH)
          println(GIT_PREVIOUS_COMMIT)
          println(GIT_PREVIOUS_SUCCESSFUL_COMMIT)
          println(GIT_URL)
        }
      }
    }
  }
}
