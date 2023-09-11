pipeline{
    agent any
    stages{
        stage("Clone the github repository"){
            steps{
                sh 'git clone https://github.com/ShaikAtafHussainDevOps/TECHNICAL_ASSIGNMENT.git -b master'
            }
        }
        stage("deploy"){
            steps{
                sh 'pwd'
                sh 'mv jj1/* ../../../../www/html/'
            }
        }     
    }
}
