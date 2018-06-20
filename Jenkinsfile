pipeline {
  agent any
  stages {
    stage('Test Message') {
      steps {
        echo 'There was a commit done'
        sh '''cd /srv/jenkins/playbooks/eco_account/
ansible-playbook -i hosts.yml eco_account_test_deploy.yml'''
      }
    }
  }
}