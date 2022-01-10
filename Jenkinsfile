environment example
pipeline {
 agent any
 environment {
   URL1 = "google.com"
   SSH = credentials("CENTOS")
   SSH1 = credentials("common/ssh")
 }
 stages {
   stage('ONE') {
     environment {
       URL1 = "yahoo.com"
                  }
     steps {
       sh 'echo ${URL1}'
       sh 'env'
       echo SSH
       sh 'echo ${SSH1} | base64'
           }
   }
 }
}
