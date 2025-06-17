pipeline {
    agent {
        label 'slave'
    }

    stages{
        stage('Print Hostname'){
            steps{
               sh 'hostname' 
            }
        }
        stage('Ip Address'){
            steps{
                sh 'hostname -I'
            }
        }
        stage('Cpu Details'){
            steps{
                sh 'lscpu'
            }
        }
        stage('Disk usage'){
            steps{
                sh 'df -kh'
            }
        }
        stage('Memory usage'){
            steps{
                sh 'free -h'
            }
        }
         stage('date'){
            steps{
                sh 'date'
            }
        }
    }
}
