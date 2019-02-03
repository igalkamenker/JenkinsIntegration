pipeline{
	agent any
	stages{
		stage("WhenExamples"){
			when { 
				changelog 'hello'
			}
			steps{
				echo "Yes, change log contains hello message...."
			}		}	}}
