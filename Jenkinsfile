pipeline {
  agent any
  stages {
    stage('Test') {
      steps {
        sshCommand(command: 'hostname', dryRun: true)
      }
    }

  }
}