pipeline{
  agent any
  stages('CI'){
    stage('checkout'){
      steps{
        echo 'checkout'
        checkout scm
      }
    }
    stage('Build'){
      steps{
        //script
        echo 'build'
        sh 'mvn clean install'
      }    
      }    
  }
}
