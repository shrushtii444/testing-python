pipeline {
  agent any

  stages {
    stage('Build') {
      steps{
      echo 'Building'
    }
  }
  stage('test') {
  steps {
    sh 'python -- version'
  }
}
stage('Deploy') {
  steps {
    echo 'Deploying'
  }
}
  }
}
    


