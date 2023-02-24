node {
  stage('SCM Checkout') {
    git 'https://github.com/uthayakumarM/jenkinsintegration'
  }
  stage('compile package') {
    sh 'mvn package'
  }
}
