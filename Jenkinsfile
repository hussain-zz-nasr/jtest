pipline{
    agent any
    tools{nodejs "node"}
    stages{
        stage("install Dependencies"){
            steps{
                sh 'npm install'
            }
        }
    
        stage("tests"){
            steps{
                sh 'npm test'
            }
        }
    }

}