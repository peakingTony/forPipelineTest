pipeline{

	agent any
	environment{
		mvnHome = tool 'maven'
	}
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
				script{
					if (false) {
						sh 'ls'
					}else{
						sh 'pwd'
					}
				}
			}
		}
	}
}






