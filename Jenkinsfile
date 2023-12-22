pipeline{
  agent any
  stages{
    stage("build stage"){
      steps{
        echo " build the code successfully"
       sh "javac Hello.java"
      }
    }
    stage("Test stage"){
      steps{
        echo "tested the code successfully"
       sh "java Hello"
      }
    }
    stage("Deploy"){
      steps{
        echo " deployment done"
      }
    }
  }
}
