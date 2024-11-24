pipeline {
    agent any
    
    stages {
        stage('Build') {
            steps {
                sh 'echo This is Build'
                //sh 'sleep 10'
            }
        }
        stage('Test') {
            steps {
                sh 'echo This is test'
                sh 'env'
            }
        }
        stage('Deploy') {
            steps {

                    sh 'echo This is deploy'
                    //error 'pipeline failed'

            }
        }
    }   