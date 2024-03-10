pipeline {   
    agent any

    stages {   
        stage('Master branch latest') { 
            steps { 
               sh 'echo "This is master branch latest"' 
            }
        }
     
        stage('sprint1') { 
            steps { 
               sh 'echo "sprint1 application..."'
            }
        }

        stage("Deploy application") { 
             steps { 
                sh 'echo "Deploying application..."'
            }
        }  
    }
}
