pipeline {
       agent any
	stages {
	     stage('Init') {
		   steps {
			 echo 'jenkins code pipeline session!'
		    }
	      }
 	      stage('Build') {
		    steps {
			   echo 'Building sample Maven project'
		     }
               }
		
	       stage('Deploy in Staging') {
 		     steps {
			    echo 'Deploying in staging area'
	             }
  		}

	  }
}
