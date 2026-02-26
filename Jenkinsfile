pipeline {
  agent any
  stages {
    stage('clone') {
      steps {
        git url: 'https://github.com/Deepa1626/jenkins-simple-demo.git',
          branch: 'main'
      }
    }
    stage('Run Script') {
      steps {
        sh 'chmod +x script.sh'
        sh './script.sh'
      }
    }
  }
}
