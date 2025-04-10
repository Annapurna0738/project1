pipeline{
    agent any
    stages{
        stage('server hostname'){
            steps{
                sh 'hostname'
            }
        }
        stage('server uptime'){
            steps{
                sh 'uptime'
            }
        }
        stage('server diskusage'){
            steps{
                sh 'df -h'
            }
        }
        stage('server cpu usage'){
            steps{
                sh 'lscpu'
            }
        }
        stage('server memory'){
            steps{
                sh 'free -h'
            }
        }
    }
}
