pipeline
{
  agent any
  stages
  {
    stage("GIT")
    {
      steps
      {
        git "https://github.com/amanbaghel101/Task_Feb_26/tree/feature"
      }
    }
    stage("Run")
    {
      steps
      {
        sh "java Demo.java"
	sh "python main.py"
      }
    }
  }
}
