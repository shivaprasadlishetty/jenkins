// pipeline {
//     agent any
//
//     stages {
//         stage('Hello') {
//             steps {
//                 echo 'Hello World'
//                 echo bye world'''
//                 mail bcc: '', body: 'Text', cc: '', from: '', replyTo: '', subject: 'Text', to: 'l.shivaprasad.160@gmail.com'
//
//             }
//         }
//     }
// }

// Agent example
//
// pipeline {
//  agent any
//  agent none
//  agent {
//    node { 'workstation'}
//  }
//  agent {
//    label { 'ANSIBLE && CENTOS' }
//  }
//
//   stages {
//     stage('sample') {
//       agent { label 'UBUNTU' }
//       steps {
//         sh 'echo heloo'
//       }
//     }
//   }

pipeline {
 agent any
 options { disableConcurrentBuilds() }
 stages {
   stage('ONE') {
     steps {
       sh 'sleep 10'
     }
   }
 }
}