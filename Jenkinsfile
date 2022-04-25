pipeline{
  agent none
  stages('CI'){
    stage('checkout'){
      steps{
        echo 'checkout'
      }
    }
    stage('Build'){
      steps{
        //script
        echo 'build'
        sh 'mvn clean install'
      }
    }
    stage('Test'){
      steps{
        //script
        echo 'Test'
      }
    }
  }
}