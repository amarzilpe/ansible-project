pipeline{
  agent any
  stages{
    stage('pulling source code from git repo'){
      steps{
        sh 'ansible-playbook deploy.yml'
      }
    }
  }
}
