pipeline {
    agent any

    tools {
        maven 'mvn-3.5.4'

        }
stages { 
    stage('Build') {
	steps {
	    sh "mvn clean package spring-boot:repackage"
	    sh "printenv"
           }
         }
      }
}
