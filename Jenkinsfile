pipeline {
    agent any 
    
    stages {
    	stage ('build') {
    		
    		steps {
    			withMaven(maven : 'Maven360'){
    				sh 'mvn --version'
    			}
    		}
    	}
    
   	}
}