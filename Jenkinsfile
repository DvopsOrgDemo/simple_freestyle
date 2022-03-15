pipeline{
    agent any
    stages{
        stage('git source'){
            steps{
                script{
                     'git clone https://github.com/DvopsOrgDemo/simple_freestyle.git'
                }
                
            }
        }
        stage('build'){
            steps{
                script{
                    mvn clean install
                }

            }
                
        }
        
    }
}