pipeline{

agent none

stages {
      
        stage ( 'Build for c-source' ){
              agent{ label 'jenkin-slave1' }
              steps{
                   echo "executing makefile"
                   sh 'sleep 10'
                    pwd
                    sh 'git clone https://github.com/bhanurekha09/csource.git'
                    sh 'cd /home/ec2-user/jenkins/workspace/pipeline-18-20/csource'
                    sh 'echo "executing on jenkin-slave" '
                    sh 'ls'
                    sh 
                    sh 'cd csource'
                    sh 'ls'
                    sh 'make'
                    sh 'rm -rf csource'
                   }    
         }         
}   
      
      
}
