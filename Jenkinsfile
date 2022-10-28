node{
      stage('Clone') {
          checkout scm
      }
      stage('SSH') {
        sh "ansible-playbook -i inventaire playbook.yml"
      }
}

