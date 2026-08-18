pipeline{
  agent any
  stages{
    stage('compile'){
      steps{
        sh 'pyc HelloWorld.py'
      }
    }
    stage('Run'){
      steps{
        sh'py HelloWorld'
      }
    }
  }
}
