pipeline{
    agent any
    stages{
        stage("SCM git"){
            steps{
                //echo "this is git clone section"
                git 'https://github.com/clouddevops0201/evening-pipelineexample.git'
            }
            
        }
        stage("test"){
            steps{
                echo "this is test section"
                //bat 'mvn clean install'
            }
            
        }
		stage("UAT"){
            steps{
                echo "this is uat section"
                //bat 'mvn clean install'
            }
            
        }
		stage("PROD"){
            steps{
                echo "this is prod section"
                //bat 'mvn clean install'
            }
            
        }
		stage("perf"){
            steps{
                echo "this is perf section"
                //bat 'mvn clean install'
            }
            
        }
        
        
    }
}