pipeline {
    agent any
    stages {
        stage('cloudformation') {
            steps {
                sh 'aws cloudformation create-stack  --stack-name myteststack  --template-body S3Bucket.json  --region us-east-1'
            }
        }
    }
}
