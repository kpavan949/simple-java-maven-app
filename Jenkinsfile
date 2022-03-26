pipeline {
  agent any

  stages {
   stage ('git') {
   steps{
   git 'https://github.com/kpavan949/simple-java-maven-app.git'
   }
   }
   stage ('build') {
   steps{
   sh 'mvn clean install'
   }
   }
    
    
   }
}

