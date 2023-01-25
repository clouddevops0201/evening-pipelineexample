pipeline{
    agent any
    stages{
        stage("SCM git"){
            steps{
                //echo "this is git clone section"
                git 'https://github.com/clouddevops0201/evening-pipelineexample.git'
            }
            
        }
        stage("MAVEN Build"){
            steps{
                //echo "this is build section"
                bat 'mvn clean install'
            }
            
        }
        
        
    }
}