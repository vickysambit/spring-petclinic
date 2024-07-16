#!groovy
pipeline {
    agent none
   stages {     
    stage('Maven Install') {
      agent {         
       docker {          
         image 'maven:3.5.0'         
     }       
  }       
  steps {
       sh '/home/gitops-user/spring-petclinic/mvnw package'
       }
     }
   }
 }
