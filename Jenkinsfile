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
			sh "python3 fun_test.py"
				}
		}
	}
}
