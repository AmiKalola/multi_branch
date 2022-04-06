pipeline {
    agent any
    stages{
        stage('build'){
            steps{
                echo "hello this is buils stage!!"
            }
        }
        stage('git clone'){
            steps{
                git branch: 'dev', url: 'https://github.com/Sonu0803/demo1.git'
            }
        }
    }
}
