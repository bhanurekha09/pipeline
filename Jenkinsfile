pipeline{

agent none

stages {
      
        stage ( 'Build for c-source' ){
              agent{ label 'jenkins-slave1' }
              steps{
                   echo "executing makefile"
                   sh 'sleep 10'
                   sh 'git clone https://github.com/bhanurekha09/csource.git'
                   cd /var/lib/jenkins/workspace/c-project-build
                   make
                   }    
         }         
}   
      
      
}
