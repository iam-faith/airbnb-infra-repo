pipeline {
    agent any
    
    
    tools {
        terraform 'Terraform'
    }
    

    stages {
        stage('Git checkout') {
            steps {
                echo 'Cloning the project codebase....'
                git branch: 'main', url: 'https://github.com/iam-faith/airbnb-infra-repo.git'
                // sh 'pwd'
                // sh 'ls'

            }
        }
        
        stage('Terraform init') {
            steps {
                echo 'Terraform init....'
                sh 'terraform init'
            }
        }
        
        
        
        stage('Terraform validate') {
            steps {
                
                sh 'terraform validate'
            }
        }
        
        
        
         stage('Terraform plan') {
            steps {
               
                sh 'terraform plan'
            }
        }
        
        
        
        //  stage('Checkov scan') {
            // steps {
            //    
                // sh '''
                // sudo pip3 install checkov
                // 
                // checkov -d . --skip-check CKV_AWS_79,CKV2_AWS_41
                // 
                // '''
            // }
        // }
        
        
        
        
        
        // stage('Manual approval') {
            // steps {
            //    
            //    input 'Deploy the infrastructure?'
            // }
        // }
        
        
        
        stage('Terraform apply/destroy') {
            steps {
               
                sh 'terraform apply --auto-approve'
                sh 'terraform ${action} --auto-approve'
            }
        }        
        
    }
 
}
