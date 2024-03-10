pipeline {   
    agent any

    stages {   
        stage('Sprint1 branch') { 
            steps { 
               sh 'echo "This is master branch"' 
            }
        }
     
        stage('test') { 
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
