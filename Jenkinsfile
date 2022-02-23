pipeline {
  
  agent {label 'slave'}
  
  tools {
    maven 'mvn'
    jdk 'jdk'
  }
  stages {
  
    stage ('Build') {
      steps {
        sh 'mvn clean'
        sh 'mvn install'
        
       }
     }
    stage('Test'){
      steps{
        sh 'mvn test'
        
      }
    }
    
   }
}
