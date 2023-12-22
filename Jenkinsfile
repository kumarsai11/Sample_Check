pipeline{
  agent any
  stages{
    stage("build stage"){
      steps{
        echo " build the code successfully"
        javac Hello.java
      }
    }
    stage("Test stage"){
      steps{
        echo "tested the code successfully"
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
