pipeline {
	agent any
	parameters {
		choice(
			choices: 'yes\nno',
			description: 'want to build?',
			name: 'Requested_Action')
	}
	stages {
		stage ('build') {
			when {
				expression { params.Requested_Action =='yes' }
	
		step {
			echo "Hello builder" }
	}
}
}
}		
