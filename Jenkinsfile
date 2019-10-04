pipeline {
  agent any

  tools {nodejs "node"}

  stages {

    stage('Cloning Git') {
      steps {
        git 'https://github.com/codeyMcCodeStein/test.git'
      }
    }

    stage('Install dependencies') {
      steps {
        sh 'npm install'
      }
    }

    stage('Test') {
      steps {
         sh 'npm test'
      }
    }
    stage('Build'){
    steps{
      echo 'Is this working yda;jfs;klsjfdks;aldsfsadf?'
    }
    }
  }
}
