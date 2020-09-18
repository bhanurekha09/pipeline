pipeline{

agent none

stages {
      
        stage ( 'Build for c-source' ){
              agent{ label 'jenkin-slave1' }
              steps{
                   echo "executing makefile"
                   sh 'sleep 10'
                    sh 'pwd'
                    sh 'git clone https://github.com/bhanurekha09/csource.git'
                    sh 'pwd'
                    sh 'echo "executing on jenkin-slave" '
                    sh 'ls'
                    sh 'cd csource'
                    sh 'ls'
                    sh 'make'
                    sh 'rm -rf csource'
                   }    
         }         
}   
      
      
}
