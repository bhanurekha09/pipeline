pipeline{

agent none

stages {
      
        stage ( 'Build for j-source' ){
              agent{ label 'jenkin-slave2' }
              steps{
                   echo "executing makefile"
                  
                    sh 'pwd'
                    sh 'https://github.com/bhanurekha09/java.git'
                    sh 'pwd'
                    sh 'echo "executing on jenkin-slave" '
                    sh 'ls'
                    sh 'mvn clean install'
         }         
}   
      
      
}
