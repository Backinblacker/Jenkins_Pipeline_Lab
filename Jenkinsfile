pipeline {
  agent any
  stages{
    stages ('Test') {
      steps{
        sh 'echo "Running test stage..."'
      }
    }
    stages ('Build') {
      steps{
        sh 'echo "Building Application..."'
      }
    }
    stages ('Docker') {
      steps{
        sh 'echo "Building image and pushing to Docker Hub..."'
      }
    }
    stages ('Deploy') {
      steps{
        sh 'echo "Deploying application to EC2 Instance..."'
      }
    }
  }
}
