pipeline {
	agent any
	stages {
		stage ('build') {
			echo 'Build'
		}
		stage ('test: integration-&-quality') {
			echo 'Test_Integeral'
		}
		stage ('test: functional') {
			echo 'Test_Functional'
		}
		stage ('test: load-&-security') {
		echo 'Test_Load_Security'
		}
		stage ('approval') {
			echo 'Approved'
		}
		stage ('deploy:prod') {
		echo 'Deployed'
		}
	}
}