#!groovy

node('master')
{
stage('Deploy')

        {
     checkout scm
       env = "${env.JOB_BASE_NAME}".split("-").last()
                
                sh 'echo "$env"'
              
                
        }
}

