pipeline {   
    agent any

    stages {   
        stage('Master') { 
            steps { 
               sh 'echo "This is master branch.."' 
            }
        }
     
        stage('sprint1') { 
            steps { 
               sh 'echo "This is Sprint1 branch and file updated. sprint1 is now live"'
            }
        }
     
        stage("hotfix") { 
             steps { 
                sh 'echo "This is hotfix branch"'
            }
        }  
    }
}
