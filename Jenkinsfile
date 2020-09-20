pipeline{

agent none

      stages{ 
           
                  
                 stage( 'STAGE 1 and STAGE 2' ) {
                       parallel {
                             stage ( 'STAGE 1' ){
                              agent { label 'master' }
                              steps {
                              sh 'sleep 10'
                         }
                  }
            
            
                  stage ( 'STAGE 2' ) {
                       
                        agent { label 'trigger-deploy' }
                        steps {
                              sh 'sleep 10'
                        }
                        
                  }
                       }
                 }
            
            
                      stage( 'STAGE 3' ){
                        agent { label 'master' }
                        steps {
                              sh 'sleep 10'
                        }          
                  }
                  
                  
                  stage( 'STAGE 4'){
                        agent { label 'trigger-deploy' }
                        steps {
                              sh 'sleep 10'
                        }
                  }
            
      }
}
                        
                        
                        
      
      
                          
                    
                  
