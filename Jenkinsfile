pipeline{

agent none

stages {
      
        stage ( 'Build for j-source' ){
              agent{ label 'trigger-deploy' }
              steps{
                   echo "executing makefile"
                  
                    sh 'pwd'
                    sh 'git clone https://github.com/bhanurekha09/csource.git'
                    sh 'pwd'
                    sh 'echo "executing on jenkin-slave" '
                    sh 'ls'
                    sh 'cd  csource'
                     sh 'pwd'
                    sh 'ls'
                    sh 'make'
                    sh 'rm -rf csource'
                   }    
         }         
}   
      
      
}
