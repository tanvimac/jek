pipeline{
    agent any
    stages{
        stage('repository'){
            steps{
                echo "hello"
            }
        }
        stage('build'){
            steps{
                sh 'docker build -t redapp .'
            }
        }
    }
}