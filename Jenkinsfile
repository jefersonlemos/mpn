// def bucket = 'deployment-packages-mlabouardy'
// def functionName = 'Fibonacci'
// def region = 'eu-west-3'

node('master'){
    stage('Checkout'){
        checkout scm
    }

    stage('Test'){
        sh 'serverless deploy --stage dev -v'
    }
}





