pipeline{

    agent any

    stages{
        stage('build'){
         steps{
            sh 'npm install'
         }
        }
        stage('test'){
            sh 'echo  "testing the application"'
        }
        stage('deploy'){
            steps{
                sh 'echo "deploying the application" '
            }
        }
    }
}