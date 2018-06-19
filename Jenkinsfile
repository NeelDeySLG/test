pipeline {
  agent any
  stages {
    stage('Test Message') {
      steps {
        echo 'There was a commit done'
        sh '''cd ~/playbooks/eco_account
ansible -i ~/playbooks/eco_account/hosts.yaml -m ping testing'''
      }
    }
  }
}