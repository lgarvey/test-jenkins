node {
  withCredentials([string(credentialsId: 's3bucket2', variable: 'S3_BUCKET2'), string(credentialsId: 's3bucket', variable: 'S3_BUCKET')]) {
     echo "hello $S3_BUCKET / $S3_BUCKET2"
  }

  echo sh(returnStdout: true, script: 'env')

  def monkey = env.MONKEY

  println(env)
}
