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
                sh'sudo systemctl status jenkins'
            }
        }
        stage('5-Afeez'){
            steps{
                sh 'sudo systemctl status jenkins'
            }
        }
        stage('6-Afeez'){
            steps{
                sh 'ps -ef'
            }
        }
        stage('7-Aubin'){
            steps{
                sh 'sudo systemctl status jenkins'
            }
        }
        stage('8-Aubin'){
            steps{
                sh 'ps -ef'
            }
        }
        stage('9-Yomi'){
            steps{
                sh 'sudo systemctl status jenkins'
            }
        }
        stage('10-Yomi'){
            steps{
                sh 'ps -ef'
            }
        }
        stage('11-Olu'){
            steps{
                sh 'sudo systemctl status jenkins'
            }
        }
        stage('12-Olu'){
            steps{
                sh 'ps -ef'
            }
        }
        stage('13-Tunde'){
            steps{
                sh 'sudo systemctl status jenkins'
            }
        }
        stage('14-Tunde'){
            steps{
                sh 'ps -ef'
            }
        }
    }
}
