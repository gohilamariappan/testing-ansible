#!groovy

node('master')
{
stage('Deploy')

        {
     checkout scm
       def env = "${env.JOB_BASE_NAME}".split("-").last()
                
             sh '''
		enviroment = $ (echo "$JOB_BASE_NAME" | cut -d '-' -f 1)
		echo  "$environment"
		'''

              
                
        }
}

