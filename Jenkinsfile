pipeline{
	agent any
	stages{
		stage("first"){
			steps{
				echo 'hello dylan'
				}
		}
		stage("run test"){
			steps{
			echo 'python3'
			bat('python3 fun_test.py')
				}
		}
	}
}
