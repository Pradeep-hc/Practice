pipeline {
    agent any 
    stages {
        stage('BUILD'){
            steps {
                echo "Build stage"
                sh "sleep5"
            }
        }

        stage('TEST'){
            steps {
                echo "Test stage"
                sh "sleep 5" 

            }
        }
        stage('DEPLOY'){
            steps {
                echo "Deploy stage"
                sh "sleep 5"
            }
        }

        stage('END'){
            steps {
                echo "Last stage"
                sh "sleep 5"
            }
        }
    }
}