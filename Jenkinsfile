pipeline {
    agent any
    stages{
        stage('git clone'){
            steps{
                git branch: 'main', url: 'https://github.com/AmiKalola/multi_branch.git'
            }
        }
        
        stage('test'){
            steps{
                echo "Testing completed!!"
            }
        }
        
        stage('build'){
            steps{
                echo "hello this is buils stage!!"
            }
        }
    }
}
