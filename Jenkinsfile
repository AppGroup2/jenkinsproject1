pipeline {
    agent any
    stages{
        stage('1-clone'){
            steps{
                checkout scmGit(branches: [[name: '*/main']], extensions: [], userRemoteConfigs: [[url: 'https://github.com/AppGroup2/jenkinsproject1.git']])
            }
        }    
        stage('2-process status'){
            steps{
                sh 'ps -ef'
            }
        }
        stage('3-jenkins status'){
            steps{
                sh 'sudo systemctl status jenkins'
            }
        }
    }
}