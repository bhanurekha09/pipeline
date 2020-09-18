pipeline{

agent none

stages {
      
        stage ( 'Build for c-source' ){
              agent{ label 'jenkin-slave1' }
              steps{
                   echo "executing makefile"
                   sh 'sleep 10'
                   sh 'git clone https://github.com/bhanurekha09/csource.git'
                   sh 'cd /home/ec2-user/jenkins/workspace/pipeline-18-20/csource'
                    sh 'make'
                    sh 'rm -rf csource'
                   }    
         }         
}   
      
      
}
