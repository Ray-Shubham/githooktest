pipeline{
agent any
  stages{
  stage('Testing webhook'){
  steps{
    echo "Success"
  }}
  stage('email notification'){
    steps{
      mail bcc: '', body: 'This is a testing of build  email notification ', cc: '', from: '', replyTo: '', subject: 'Jenkins build ', to: 'gautham.kukutla@gmail.com'
    }}}
}
