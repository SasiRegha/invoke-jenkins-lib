@Library('jen-pipe-lib') _

pipeline
{
	agent any
	stages
	{
		stage('from jenkinsfile')
		{
			steps
			{
				echo "from jenkinsfile..."
			}
		}
		stage('from lib')
		{
			steps
			{
				fromLibarary()
				fromTestBranch()
				echo "HELLOOOOOOOOO"
			}
		}
	
	}
}

