pipeline{
  
  agent any
  
  stages {
    stage('Clean'){
      steps{
        sh 'mvn clean'
      }
    }
    stage('Test'){
      steps{
        sh 'mvn test'
      }
    }
    stage('Package'){
      steps('Package'){
        sh 'mvn package'
      }
    }
  }
  
}
