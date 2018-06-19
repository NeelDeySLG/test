pipeline {
  agent any
  stages {
    stage('Test Message') {
      steps {
        echo 'There was a commit done'
        sh '''cd /home/centos/playbooks/eco_account
ansible -i hosts.yaml -m ping testing'''
      }
    }
  }
}