pipeline
{
  agent any
  stages
  {
    stage("GIT")
    {
      steps
      {
        git "https://github.com/udayakumar99/jenkins_lin.git"
      }
    }
    stage("Run")
    {
      steps
      {
        "javac demo.java"
        "java demo.java"
      }
    }
  }
}

