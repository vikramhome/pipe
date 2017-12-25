pipeline {
	agent any
	parameters {
		choice(
			choices: 'yes\nno\nMaybe',
			description: 'want to build?',
			name: 'Requested_Action')
	}
	stages {
		stage ('build') {
			when {
				expression { params.Requested_Action =='yes' }
			}
		steps {
			echo "Hello builder" }
		}
	}
}		
