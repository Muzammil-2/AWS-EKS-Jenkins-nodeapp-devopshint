pipeline {
    agent any 
         tools {
  nodejs 'nodejs_tool'
   }
    stages {
        stage('Checkout_Codes') { 
            steps {
                git branch: 'main', credentialsId: 'github_id', url: 'https://github.com/Muzammil-2/AWS-EKS-Jenkins-nodeapp-devopshint.git'
            }
        }
       stage('build') { 
            steps {
              sh 'npm i'
            }
        }
        /*stage('Deploy') { 
            steps {
                // 
            }
        }
     */
    }
}