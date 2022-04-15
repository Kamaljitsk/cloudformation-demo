pipeline {
    agent any
    stages {
        stage('Submit Stack') {
            steps {
            sh "aws cloudformation create-stack --stack-name demo-s3bucket --template-body file://simplests3cft.json --region 'us-east-1'"
              }
             }
            }
 }
