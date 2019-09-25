#!groovy

node('master')
{
stage('Deploy')

        {
     checkout scm
       def env = "${env.JOB_BASE_NAME}".split("-").last()
                
             sh """ 
             environment = ${env}
             echo ${environment}
                """
              
                
        }
}

