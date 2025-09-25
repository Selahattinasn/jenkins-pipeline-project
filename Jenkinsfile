pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                echo "Conpilin java code"
                sh 'javac Hello.java'
                sh 'python3 pipeline.py'
            }
        }
 stage('run') {
            steps {
                echo "Running java code"
                sh 'java Hello'
             
            }
        }
    }
}