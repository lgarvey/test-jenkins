node {
  withCredentials([string(credentialsId: 's3bucket2', variable: 'S3_BUCKET')]) {
    echo "$S3_BUCKET"  
    sh 'echo $S3_BUCKET'

    if(env.S3_BUCKET == "my magical s3 bucket"){
       echo "hooraaah"
    }
    else {
       echo "arrrrrgh"
    }
  }
    echo 'Hello World'
}
