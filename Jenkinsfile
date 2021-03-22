pipeline {

  agent any
  stages {
   

    stage('commit') {
    
      steps {                
      git 'https://github.com/Indhuja-R/php.git'

      }
    }
    stage('build') {
    
       def mvnHome=tool name: 'maven', type: 'maven'
       sh "${ mynHome}/bin/mvn package"
    
      
    }
    stage('test') {
    
      steps {                
          sh "mvn clean verify"

      }
    }
    
  }
}
