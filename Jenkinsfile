node{
  stage('SCM Checkout'){
  git 'https://github.com/benod44/SpringJenkinsDocker'
  }
  
  stage('Compile-Package'){
  sh 'mvn package'
  }
}
