node{
      stage('Clone') {
          checkout scm
      }
      stage('Ansible') {
        ansiblePlaybook (
            inventory: 'hosts.yaml',
            playbook: 'playbook.yaml',
            colorized: true,
        )
      }
}

