pipeline{

	agent any
	stages{
		stage('Preparation'){
			when{
				branch 'master'
			}
			steps{
				git 'https://gitee.com/peaking/forJenkinsPipelineTest.git'
			}
		}
		stage('Build'){
			steps{
				sh 'pwd'
			}	
		}

	}
}






