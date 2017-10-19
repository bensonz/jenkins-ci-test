node {
  stage('Preqeq') {
    checkout scm
  }

  stage('Build image') {
    sh "docker build -t ci-test ."
  }

  stage('Run tests') {
    sh "echo 'pretending to run test...'"
  }

  stage('Push image to registry') {
    sh "docker images"
  }

  stage("Deploy Application") {
    sh "echo 'pretending to deploy application'"
  }
}
