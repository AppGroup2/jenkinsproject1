pipeline {
    agent any
    stages{
        stage('1-clone'){
            steps{
                checkout scmGit(branches: [[name: '*/main']], extensions: [], userRemoteConfigs: [[url: 'https://github.com/AppGroup2/jenkinsproject1.git']])
            }
        }    
        stage('2-christian ps'){
            steps{
                sh 'ps -ef'
            }
        }
        stage('3-christian jenkins status'){
            steps{
                sh 'sudo systemctl status jenkins'
            }
        }
        stage('3-Bolatito'){
            steps{
                sh'ps -ef'
            }
         }
        stage('4-Bolatito'){
            steps{
                sh'sudo systemctl status Jenkins'
            }
        }
        stage('5-Afeez'){
            steps{
                sh'sudo systemctl status Jenkins'
            }
        }
        stage('6-Afeez'){
            steps{
                sh'ps -ef'
            }
        }
    }
}