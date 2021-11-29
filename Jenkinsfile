node('master') {
    checkout scm
    stage('Build') {
            sh 'echo hello world'
    }
}
// pipeline {
//     agent { docker { image 'maven:3.3.3' } }
//     stages {
//         stage('build') {
//             steps {
//                 sh 'mvn --version'
//             }
//         }
//     }
// }