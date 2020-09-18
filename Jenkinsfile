pipeline{

agent none

stages {
      
        stage ( 'Build for j-source' ){
              agent{ label 'master' }
              tools { 
                    jdk 'JDK 9.0.d' 
                    
                 
    }
              
              steps{
                   echo "executing makefile"
                  
                    sh 'pwd'
                    sh 'git clone https://github.com/bhanurekha09/java.git'
                    sh 'pwd'
                    sh 'echo "executing on jenkin-slave" '
                    sh 'ls'
                    sh 'mvn clean install'
         }         
}   
      
      
}
}
