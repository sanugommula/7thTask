pipeline {
	    agent any
	    triggers {
	        upstream 'task71, task72, '
	    }
	    stages {
	      stage('FIRST-JOB'){
	        steps
          {
	    git 'https://github.com/sanugommula/7thTask.git'
	        }
	  }
	        stage('Example') {
	            steps {
	                echo 'Hello World'
	            }
	        }
	    }
	}
