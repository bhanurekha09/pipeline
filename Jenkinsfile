pipeline{
      agent none
      
      stages{
      
            stage('STAGE 1'){
                    agent { label 'c-on-slave1'  }
                    
                    steps{
                    sh 'sleep 10'
                    }
            }
            
            stage( 'STAGE 2'){
                     agent { label 'java-on-slave' }
                     steps{
                     sh 'sleep 10'
                     }
            }
            
            
            stage( 'STAGE 3'){
                  agent { label 'master' }
                  steps{
                  sh 'sleep 10'
                  }
            }            
            
             stage( 'STAGE 4' ){
                   agent { label 'c-project-build' }
                    steps{
                    sh 'sleep 10'
                        }
                  }
                  
                  stage( 'STAGE 5' ){
                        agent { label 'c-on-slave2' }
                        steps{
                              sh 'sleep 10'
                        }
                        
                  }
            
            }             
           
}
