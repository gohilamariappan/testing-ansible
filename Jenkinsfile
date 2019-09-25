#!groovy

node('master')
{
stage('Deploy')

        {
     checkout scm
       sh ''' env = "${env.JOB_BASE_NAME}".split("-").last()
                
                echo "$env"
                '''
              
                
        }
}

