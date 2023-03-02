pipeline{
    agent {label "slave1" }
    stages{
//         stage('S3download'){
//             steps{
//                 withAWS(credentials:'awscredentials', region:'us-east-1'){
//                     s3Download(file: 'rlvapus7tuy7veffcwwtwq44ke.json.gz', bucket:'reminder-sqlabs-alexk',path: "AWSDynamoDB/01676567735754-39122b3a/data/rlvapus7tuy7veffcwwtwq44ke.json.gz")
//                 }
//             }
//         }
        stage('Python'){
            steps{
                sh "echo THIS IS PYTHON VERSION:"
                sh "python3 --version"
                sh "python3 first_example.py"
            }
        }
    }
}