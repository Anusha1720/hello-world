pipeline {
	   agent any
	

	  stages {
	    stage('Checkout') {
	      steps {
	        echo 'Checkout'
	        checkout scm
	      }
	    }
	

	    stage('Build') {
	      steps {
	        Echo 'Build'
	        sh 'mvn clean Package'
	      }
	    }
	  }
	

	}
