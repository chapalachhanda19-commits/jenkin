pipeline {
    agent any
    stages{
        stage('download code') {
            steps {
                checkout scm
            }
        }
        stage("sho version") {
            step{
                sh "python3 --verson"
            }
        }
        stage("run the code") {
            step{
                sh "python3 read.py"
            }
        }
        
    }
}