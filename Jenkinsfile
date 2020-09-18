pipeline{
      agent none
      
      stages{
      
            stage('STAGE 1'){
                    agent { label 'master' }
                    
                    steps{
                    sh 'sleep 10'
                    }
            }
            
            stage( 'STAGE 2'){
                     agent { label 'jenkin-slave1' }
                     steps{
                     sh 'sleep 10'
                     }
            }
            
            
            stage( 'STAGE 3'){
                  agent { label 'jenkin-slave2' }
                  steps{
                  sh 'sleep 10'
                  }
            }            
            
             stage( 'STAGE 4' ){
                   agent { label 'jenkin-slave1' }
                    steps{
                    sh 'sleep 10'
                        }
                  }
                  
                  stage( 'STAGE 5' ){
                        agent { label 'master' }
                        steps{
                              sh 'sleep 10'
                        }
                        
                  }
            
            }             
           
}
