pipeline{
  stages{
    stage('Build'){
      steps{
        echo 'Début du build'
      }
    }
    stage('Test'){
      steps{
        if (fileExists('index.html')) {
            echo 'Yes'
        } else {
            echo 'No'
              }
      }
    }
  }
}
