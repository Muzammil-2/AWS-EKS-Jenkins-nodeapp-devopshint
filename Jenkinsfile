pipeline {
    agent any 
    stages {
        stage('Checkout_Codes') { 
            steps {
                git branch: 'main', credentialsId: 'github_id', url: 'https://github.com/Muzammil-2/AWS-EKS-Jenkins-nodeapp-devopshint.git'
            }
        }
   /*     stage('Test') { 
            steps {
                // 
            }
        }
        stage('Deploy') { 
            steps {
                // 
            }
        }
     */
    }
}