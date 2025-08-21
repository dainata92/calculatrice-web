pipeline{
  agent any
  stages{
    stage('Build'){
      steps{
        echo 'Début du build'
      }
    }
    stage('Test'){
      steps{
        script{
        if (fileExists('index.html')) {
            echo 'Yes'
        } else {
            echo 'No'
              }
        }
      }
    }
  }
}
