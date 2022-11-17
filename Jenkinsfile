pipeline {
   
    agent {
        kubernetes {            
            yamlFile 'config/builder.yml'
        }
    }

    environment {
        IMAGE = 'cots-image'
    }

    stages {

        stage("Build") { 
            steps{ 
                script{

                }
            }                                        
        }
            
    }       
}
