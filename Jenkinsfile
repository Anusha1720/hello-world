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
		// scripting
	        echo 'Build'
	        sh 'mvn clean package'
	      }
	    }
	  }
	

	}
