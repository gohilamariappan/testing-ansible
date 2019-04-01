#!groovy

node('server_build_slave')
{
stage('Deploy')

        {
         sh 'ansible-playbook -i /home/jenkins/ansible/tasks/inventory/local /home/jenkins/ansible/tasks/playbook.yml'
        }
}

