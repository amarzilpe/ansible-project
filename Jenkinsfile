pipeline{
  agent any
  stages{
    stage('pulling source code from git repo'){
      steps{
        git branch: 'deploy-war', url: 'https://github.com/amarzilpe/ansible-project.git'
      }
      steps{
        sh 'ansible-playbook deploy.yml'
      }
    }
  }
}
