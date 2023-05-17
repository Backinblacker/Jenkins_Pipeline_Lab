pipeline {
  agent any
  stages{
    stage ('Test') {
      steps{
        sh 'echo "Running test stage..."'
      }
    }
    stage ('Build') {
      steps{
        sh 'echo "Building Application..."'
      }
    }
    stage ('Docker') {
      steps{
        sh 'echo "Building image and pushing to Docker Hub..."'
      }
    }
    stage ('Deploy') {
      steps{
        sh 'echo "Deploying application to EC2 Instance..."'
      }
    }
  }
}
