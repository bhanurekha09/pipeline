pipeline{

agent none

      stages { 
            parallel {
                  
                 stage( 'STAGE 1' ) {
                 
                  agent { label 'jenkin-slave1' }
                  steps {
                         sh 'sleep 10'
                         }
                  }
            
            
                  stage ( 'STAGE 2' ) {
                        
                        agent { label 'jenkin-slave2' }
                        steps {
                              sh 'sleep 10'
                        }
                        
                  }
                  
            }
            
            parallel {
                  stage( 'STAGE 3' ){
                        agent { label 'master' }
                        steps {
                              sh 'sleep 10'
                        }          
                  }
                  
                  
                  stage( 'STAGE 4'){
                        agent { label 'jenkin-slave1' }
                        steps {
                              sh 'sleep 10'
                        }
                  }
            }
      }
}
                        
                        
                        
      
      
                          
                    
                  
