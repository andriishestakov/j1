pipeline {
  agent any
  stages {
    stage('') {
      steps {
        ansiblePlaybook(playbook: 'facts.yaml', colorized: true, inventoryContent: '192.168.43.19,')
      }
    }

  }
}