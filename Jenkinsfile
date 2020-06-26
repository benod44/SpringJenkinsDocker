node{
  stage('SCM Checkout'){
  git 'https://github.com/benod44/SpringJenkinsDocker'
  }
  
  stage('Email NOtification'){
  mail bcc: '', body: '''Alert
  jenkins build started

  Automated message''', cc: '', from: '', replyTo: '', subject: 'jenkins job', to: 'lovelyanamikamishra@gmail.com'
  }
}
