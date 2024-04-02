// pipeline {
//     agent any
//     stages {
//         stage('run') {
//             steps {
//                 echo 'Clarusway_Way to Reinvent Yourself'
//                 sh 'python3 --version'
//                 sh 'python3 pipeline.py'
//             }
//         }
//         stage('test') {
//             steps {
//                 echo 'Testing ...'
//                 sh 'ls -al'
//             }
//         }
//     }
// }

pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                echo 'Compiling the java source code'
                sh 'javac Hello.java'
            }
        }
        stage('run') {
            steps {
                echo 'Running the compiled java code.'
                sh 'java Hello'
            }
        }
    }
}
