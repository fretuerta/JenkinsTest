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
		
        stage("Clone Repo") {
            steps { 
                script { 
                    sh "git clone https://github.com/fretuerta/JenkinsTest.git"
                }      
            }
                                                               
        }

        stage("Build") { 
            steps{ 
                script{

                }
            }                                        
        }
            
    }       
}
