pipeline {
    agent any
    stages{
        stage('download code') {
            steps {
                checkout scm
            }
        }
        stage("sho version") {
            steps {
                sh "python3 --version"
            }
        }
        stage("run the code") {
            steps {
                sh "python3 read.py"
            }
        }
        
    }
}