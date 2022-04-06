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
                git branch: 'dev', url: 'https://github.com/AmiKalola/multi_branch.git'
            }
        }
    }
}
