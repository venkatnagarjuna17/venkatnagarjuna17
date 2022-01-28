
pipeline {
	agent {label 'slave' }
	stages {
		stage ('build') {
			steps {
				echo "this is my build stage"
			}
			}
		stage ('test: integration-&-quality') {
			steps {
				echo "this is my integartion stage "
			}
			
		}
		stage ('test: functional') {
			steps {
				echo "this is my functional stage"
			}
		}
		stage ('test: load-&-security') {
			steps {
				echo "this is my security stage"
			}
			
		}
		stage ('approval') {
			steps {
				echo "this is my approval stage"
			}
			
		}
		stage ('deploy:prod') {
			steps {
				echo "this is my deploy to prod stage "
			}
		
		}
	}
}
