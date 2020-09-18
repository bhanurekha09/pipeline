pipeline{
      agent none
      
      stages{
      
            stage('STAGE 1'){
                    agent { label1 'c-on-slave1'  }
                    
                    steps{
                    sh 'sleep 10'
                    }
            }
            
            stage( STAGE 2'){
                     agent { label1 'java-on-slave' }
                     steps{
                     sh 'sleep 10'
                     }
            }
            
            
            stage( 'STAGE 3'){
                  agent { label1 'master' }
                  steps{
                  sh 'sleep 10'
                  }
            }            
            
            
            }             
           
}
