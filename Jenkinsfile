pipeline{
  agent any
  stages{
    stage('Build'){
      steps{
        script{
          bat docker build -t toDoApplication .
        }
      }
    }
    stage('Test'){
      steps{
        script{
          echo "testing ... "
        }
      }
    }
    stage('Deploy'){
      steps{
        script{
          echo "deploying ..."
        }
      }
    }
  }
}