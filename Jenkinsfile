#!groovy

node('master')
{
stage('Deploy')

        {
     checkout scm

              sh '''
		environment = (echo "$JOB_BASE_NAME" | cut -d "-" -f 1)
		echo "$environment"
		'''

              
                
        }
}

