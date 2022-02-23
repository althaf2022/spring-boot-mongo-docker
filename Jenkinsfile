pipeline {
    agent {label 'slave'}
    tools {
        maven 'mvn'
        jdk 'jdk'
    }
    stages {
        stage ('build stage'){
            steps {
                sh 'mvn clean'
                sh 'mvn install'
                
            }
        }
        
         stage ('test stage'){
            steps {
                
                sh 'mvn test'
                
            }
        }
        
    }
}
