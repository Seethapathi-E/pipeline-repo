pipeline {   
    agent any

    stages {   
        stage('Master') { 
            steps { 
               sh 'echo "This is master branch"' 
            }
        }
     
        stage('sprint1dev') { 
            steps { 
               sh 'echo "This is Sprint1dev branch"'
            }
        }

        stage("Development") { 
             steps { 
                sh 'echo "This is development branch"'
            }
        }  
    }
}
