pipeline{
agent any
  stages{
  stage('Testing webhook'){
  steps{
    echo "Success"
  }}
  stage('Email Notification'){
    steps{
mail bcc: '', body: '''HI 
this is a test of jenkins mail

thanks and regards,
subham''', cc: '', from: '', replyTo: '', subject: 'testing', to: 'raysubham90@gmail.com'
    }}}
}
