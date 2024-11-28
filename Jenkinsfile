pipeline{
  agent any
    stages{
      stage('build')
      {
        steps{
        script{
          bat 'docker build -t devops-exam .'
        }
        }
      }
      stage('test')
      {
        steps{
        script
        {
          echo 'tests are running'
        }
        }
      }
      stage('deploy')
      {
        steps{
        script
        {
          echo 'deploying app'
        }
        }
      }
    }
}
