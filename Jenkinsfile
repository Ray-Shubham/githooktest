pipeline{
agent any
  stages{
  stage('Testing webhook'){
  steps{
    echo "Success"
  }}
  stage('Email Notification'){
    steps{
      mail bcc: '', body: '''This is a testing of Email notification 
thanks
Ray''', cc: '', from: '', replyTo: '', subject: 'Email Notification', to: 'raysubham90@gmail.com'
    }}}
}
