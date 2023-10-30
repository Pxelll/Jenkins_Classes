pipeline{
	agent none

	stages{
		stage("SkipDefault"){
			agent any
			options{
				skipDefaultCheckout()
			}
		steps{
			echo "Hello World"
		}
		}
	}
}
