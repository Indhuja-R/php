node {
    stage('commit') {
    
                    
      git 'https://github.com/Indhuja-R/php.git'

     
    }
    stage('build') {
    
       def mvnHome=tool name: 'maven', type: 'maven'
       sh "${ mynHome}/bin/mvn package"
    
      
    }
   
    
  
}
