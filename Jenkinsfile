pipeline {
  agent any
  stages{
    steps{
      git url:'https://github.com/demo31-hue/jenkins-simple-demo.git',
        branch:'main'
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
