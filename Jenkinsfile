pipeline{
    agent any
    stages{
        stage("cleaning"){
            steps{
                sh 'rm -r *'
            }
        }
        stage("Clone the github repository"){
            steps{
                sh 'git clone https://github.com/ShaikAtafHussainDevOps/TECHNICAL_ASSIGNMENT.git -b master'
            }
        }
        stage("deploy"){
            steps{
                sh 'pwd'
                sh 'mv * ../../../www/html/'
            }
        }     
    }
}
