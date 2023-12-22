pipeline{
  agent any
  stages{
    stage("build stage"){
      steps{
        echo " build the code successfully"
      }
    }
    stage("build"){
      steps{
       javac Hello.java
      }
    }
    stage("Test stage"){
      steps{
        echo "tested the code successfully"
      }
    }
    stage("Test"){
      steps{
       java Hello.java
      }
    }
    stage("Deploy"){
      steps{
        echo " deployment done"
      }
    }
  }
}
