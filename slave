pipeline {
  
 agent any 
  
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
   }
}
