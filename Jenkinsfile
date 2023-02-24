node {
  stage('SCM Checkout') {
    git 'https://github.com/uthayakumarM/jenkinsintegration'
  }
  stage('compile package') {
     def mvnHome = tool name: 'Maven', type: 'maven'
     sh "${mvnHome}/bin/mvn package"
  }
  
}
