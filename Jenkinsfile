pipeline{
	agent any
	stages{
		stage('Main Branch Deploy Code'){
			when{
				branch 'main'
			}
			steps{
				echo "Building Artifact from Main Branch"
				echo "Deploying code from Main Branch"
			}
		}
		stage('Develop Branch Deploy Code'){
			when{
				branch 'develop'
			}
			steps{
				echo "Building Artifact from Develop Branch"
				echo "Deploying code from Develop Branch"
			}
		}
	}
}