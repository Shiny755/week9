pipeline{
  agent any
    stages{
      stage('build')
      {
        script{
          bat 'docker build -t devops-exam .'
        }
      }
      stage('test')
      {
        script
        {
          echo 'tests are running'
        }
      }
      stage('deploy')
      {
        script
        {
          echo 'deploying app'
        }
      }
    }
}
