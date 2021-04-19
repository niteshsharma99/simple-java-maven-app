pipeline {
    
    agent none
    
   stages {
        
        stage('Build'){
            
            agent {
                label "slave1"
            }
          
          steps {
             
                echo "my master branch"
          }
        }
   }
}
