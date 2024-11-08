def COLOR_MAP = [
    'SUCCESS': 'good',
    'FAILURE': 'danger',
    ]


pipeline {
    agent any
    
    tools {
        terraform 'Terraform'
    }
    
    environment {
        AWS_ACCESS_KEY_ID     = credentials('jenkins-aws-secret-key-id')
        AWS_SECRET_ACCESS_KEY = credentials('jenkins-aws-secret-access-key')
    }

    stages {
        stage('Git Checkout') {
            steps {
                echo 'Cloning project code base into jenkins'
                git branch: 'main', credentialsId: 'git-token', url: 'https://github.com/iam-faith/airbnb-infra-repo.git'
                sh 'ls'
            }
        }
        
        stage('Terraform Version') {
            steps {
                echo 'Verifying terraform version'
                sh 'terraform --version'
            }
        }
        
        stage('Terraform Init') {
            steps {
                echo 'Initializing project'
                sh 'terraform init'
            }
        }
        
        stage('Terraform Plan') {
            steps {
                echo 'Running Terraform plan'
                sh 'terraform plan'
            }
        }         
     
     
        stage('Terraform Apply/Destroy') {
            steps {
                sh 'terraform ${action} --auto-approve'
            }
        } 
       
    }
    
    post { 
        always { 
            echo 'I will always say Hello again!'
            slackSend channel: '#jjtech-champions-devops-team', color: COLOR_MAP[currentBuild.currentResult], message: "*${currentBuild.currentResult}:* Job ${env.JOB_NAME} build ${env.BUILD_NUMBER} \n More info at: ${env.BUILD_URL}"
        }
        }    
    
}
def COLOR_MAP = [
    'SUCCESS': 'good',
    'FAILURE': 'danger',
    ]


pipeline {
    agent any
    
    tools {
        terraform 'Terraform'
    }
    
    environment {
        AWS_ACCESS_KEY_ID     = credentials('jenkins-aws-secret-key-id')
        AWS_SECRET_ACCESS_KEY = credentials('jenkins-aws-secret-access-key')
    }

    stages {
        stage('Git Checkout') {
            steps {
                echo 'Cloning project code base into jenkins'
                git branch: 'main', credentialsId: 'git-token', url: 'https://github.com/iam-faith/airbnb-infra-repo.git'
                sh 'ls'
            }
        }
        
        stage('Terraform Version') {
            steps {
                echo 'Verifying terraform version'
                sh 'terraform --version'
            }
        }
        
        stage('Terraform Init') {
            steps {
                echo 'Initializing project'
                sh 'terraform init'
            }
        }
        
        stage('Terraform Plan') {
            steps {
                echo 'Running Terraform plan'
                sh 'terraform plan'
            }
        }         
     
     
        stage('Terraform Apply/Destroy') {
            steps {
                sh 'terraform ${action} --auto-approve'
            }
        } 
       
    }
    
    post { 
        always { 
            echo 'I will always say Hello again!'
            slackSend channel: '#jjtech-champions-devops-team', color: COLOR_MAP[currentBuild.currentResult], message: "*${currentBuild.currentResult}:* Job ${env.JOB_NAME} build ${env.BUILD_NUMBER} \n More info at: ${env.BUILD_URL}"
        }
        }    
    
}
def COLOR_MAP = [
    'SUCCESS': 'good',
    'FAILURE': 'danger',
    ]


pipeline {
    agent any
    
    tools {
        terraform 'Terraform'
    }
    
    environment {
        AWS_ACCESS_KEY_ID     = credentials('jenkins-aws-secret-key-id')
        AWS_SECRET_ACCESS_KEY = credentials('jenkins-aws-secret-access-key')
    }

    stages {
        stage('Git Checkout') {
            steps {
                echo 'Cloning project code base into jenkins'
                git branch: 'main', credentialsId: 'git-token', url: 'https://github.com/iam-faith/airbnb-infra-repo.git'
                sh 'ls'
            }
        }
        
        stage('Terraform Version') {
            steps {
                echo 'Verifying terraform version'
                sh 'terraform --version'
            }
        }
        
        stage('Terraform Init') {
            steps {
                echo 'Initializing project'
                sh 'terraform init'
            }
        }
        
        stage('Terraform Plan') {
            steps {
                echo 'Running Terraform plan'
                sh 'terraform plan'
            }
        }         
     
     
        stage('Terraform Apply/Destroy') {
            steps {
                sh 'terraform ${action} --auto-approve'
            }
        } 
       
    }
    
    post { 
        always { 
            echo 'I will always say Hello again!'
            slackSend channel: '#jjtech-champions-devops-team', color: COLOR_MAP[currentBuild.currentResult], message: "*${currentBuild.currentResult}:* Job ${env.JOB_NAME} build ${env.BUILD_NUMBER} \n More info at: ${env.BUILD_URL}"
        }
        }    
    
}
def COLOR_MAP = [
    'SUCCESS': 'good',
    'FAILURE': 'danger',
    ]


pipeline {
    agent any
    
    tools {
        terraform 'Terraform'
    }
    
    environment {
        AWS_ACCESS_KEY_ID     = credentials('jenkins-aws-secret-key-id')
        AWS_SECRET_ACCESS_KEY = credentials('jenkins-aws-secret-access-key')
    }

    stages {
        stage('Git Checkout') {
            steps {
                echo 'Cloning project code base into jenkins'
                git branch: 'main', credentialsId: 'git-token', url: 'https://github.com/iam-faith/airbnb-infra-repo.git'
                sh 'ls'
            }
        }
        
        stage('Terraform Version') {
            steps {
                echo 'Verifying terraform version'
                sh 'terraform --version'
            }
        }
        
        stage('Terraform Init') {
            steps {
                echo 'Initializing project'
                sh 'terraform init'
            }
        }
        
        stage('Terraform Plan') {
            steps {
                echo 'Running Terraform plan'
                sh 'terraform plan'
            }
        }         
     
     
        stage('Terraform Apply/Destroy') {
            steps {
                sh 'terraform ${action} --auto-approve'
            }
        } 
       
    }
    
    post { 
        always { 
            echo 'I will always say Hello again!'
            slackSend channel: '#jjtech-champions-devops-team', color: COLOR_MAP[currentBuild.currentResult], message: "*${currentBuild.currentResult}:* Job ${env.JOB_NAME} build ${env.BUILD_NUMBER} \n More info at: ${env.BUILD_URL}"
        }
        }    
    
}
def COLOR_MAP = [
    'SUCCESS': 'good',
    'FAILURE': 'danger',
    ]


pipeline {
    agent any
    
    tools {
        terraform 'Terraform'
    }
    
    environment {
        AWS_ACCESS_KEY_ID     = credentials('jenkins-aws-secret-key-id')
        AWS_SECRET_ACCESS_KEY = credentials('jenkins-aws-secret-access-key')
    }

    stages {
        stage('Git Checkout') {
            steps {
                echo 'Cloning project code base into jenkins'
                git branch: 'main', credentialsId: 'git-token', url: 'https://github.com/iam-faith/airbnb-infra-repo.git'
                sh 'ls'
            }
        }
        
        stage('Terraform Version') {
            steps {
                echo 'Verifying terraform version'
                sh 'terraform --version'
            }
        }
        
        stage('Terraform Init') {
            steps {
                echo 'Initializing project'
                sh 'terraform init'
            }
        }
        
        stage('Terraform Plan') {
            steps {
                echo 'Running Terraform plan'
                sh 'terraform plan'
            }
        }         
     
     
        stage('Terraform Apply/Destroy') {
            steps {
                sh 'terraform ${action} --auto-approve'
            }
        } 
       
    }
    
    post { 
        always { 
            echo 'I will always say Hello again!'
            slackSend channel: '#jjtech-champions-devops-team', color: COLOR_MAP[currentBuild.currentResult], message: "*${currentBuild.currentResult}:* Job ${env.JOB_NAME} build ${env.BUILD_NUMBER} \n More info at: ${env.BUILD_URL}"
        }
        }    
    
}
def COLOR_MAP = [
    'SUCCESS': 'good',
    'FAILURE': 'danger',
    ]


pipeline {
    agent any
    
    tools {
        terraform 'Terraform'
    }
    
    environment {
        AWS_ACCESS_KEY_ID     = credentials('jenkins-aws-secret-key-id')
        AWS_SECRET_ACCESS_KEY = credentials('jenkins-aws-secret-access-key')
    }

    stages {
        stage('Git Checkout') {
            steps {
                echo 'Cloning project code base into jenkins'
                git branch: 'main', credentialsId: 'git-token', url: 'https://github.com/iam-faith/airbnb-infra-repo.git'
                sh 'ls'
            }
        }
        
        stage('Terraform Version') {
            steps {
                echo 'Verifying terraform version'
                sh 'terraform --version'
            }
        }
        
        stage('Terraform Init') {
            steps {
                echo 'Initializing project'
                sh 'terraform init'
            }
        }
        
        stage('Terraform Plan') {
            steps {
                echo 'Running Terraform plan'
                sh 'terraform plan'
            }
        }         
     
     
        stage('Terraform Apply/Destroy') {
            steps {
                sh 'terraform ${action} --auto-approve'
            }
        } 
       
    }
    
    post { 
        always { 
            echo 'I will always say Hello again!'
            slackSend channel: '#jjtech-champions-devops-team', color: COLOR_MAP[currentBuild.currentResult], message: "*${currentBuild.currentResult}:* Job ${env.JOB_NAME} build ${env.BUILD_NUMBER} \n More info at: ${env.BUILD_URL}"
        }
        }    
    
}
def COLOR_MAP = [
    'SUCCESS': 'good',
    'FAILURE': 'danger',
    ]


pipeline {
    agent any
    
    tools {
        terraform 'Terraform'
    }
    
    environment {
        AWS_ACCESS_KEY_ID     = credentials('jenkins-aws-secret-key-id')
        AWS_SECRET_ACCESS_KEY = credentials('jenkins-aws-secret-access-key')
    }

    stages {
        stage('Git Checkout') {
            steps {
                echo 'Cloning project code base into jenkins'
                git branch: 'main', credentialsId: 'git-token', url: 'https://github.com/iam-faith/airbnb-infra-repo.git'
                sh 'ls'
            }
        }
        
        stage('Terraform Version') {
            steps {
                echo 'Verifying terraform version'
                sh 'terraform --version'
            }
        }
        
        stage('Terraform Init') {
            steps {
                echo 'Initializing project'
                sh 'terraform init'
            }
        }
        
        stage('Terraform Plan') {
            steps {
                echo 'Running Terraform plan'
                sh 'terraform plan'
            }
        }         
     
     
        stage('Terraform Apply/Destroy') {
            steps {
                sh 'terraform ${action} --auto-approve'
            }
        } 
       
    }
    
    post { 
        always { 
            echo 'I will always say Hello again!'
            slackSend channel: '#jjtech-champions-devops-team', color: COLOR_MAP[currentBuild.currentResult], message: "*${currentBuild.currentResult}:* Job ${env.JOB_NAME} build ${env.BUILD_NUMBER} \n More info at: ${env.BUILD_URL}"
        }
        }    
    
}
def COLOR_MAP = [
    'SUCCESS': 'good',
    'FAILURE': 'danger',
    ]


pipeline {
    agent any
    
    tools {
        terraform 'Terraform'
    }
    
    environment {
        AWS_ACCESS_KEY_ID     = credentials('jenkins-aws-secret-key-id')
        AWS_SECRET_ACCESS_KEY = credentials('jenkins-aws-secret-access-key')
    }

    stages {
        stage('Git Checkout') {
            steps {
                echo 'Cloning project code base into jenkins'
                git branch: 'main', credentialsId: 'git-token', url: 'https://github.com/iam-faith/airbnb-infra-repo.git'
                sh 'ls'
            }
        }
        
        stage('Terraform Version') {
            steps {
                echo 'Verifying terraform version'
                sh 'terraform --version'
            }
        }
        
        stage('Terraform Init') {
            steps {
                echo 'Initializing project'
                sh 'terraform init'
            }
        }
        
        stage('Terraform Plan') {
            steps {
                echo 'Running Terraform plan'
                sh 'terraform plan'
            }
        }         
     
     
        stage('Terraform Apply/Destroy') {
            steps {
                sh 'terraform ${action} --auto-approve'
            }
        } 
       
    }
    
    post { 
        always { 
            echo 'I will always say Hello again!'
            slackSend channel: '#jjtech-champions-devops-team', color: COLOR_MAP[currentBuild.currentResult], message: "*${currentBuild.currentResult}:* Job ${env.JOB_NAME} build ${env.BUILD_NUMBER} \n More info at: ${env.BUILD_URL}"
        }
        }    
    
}
def COLOR_MAP = [
    'SUCCESS': 'good',
    'FAILURE': 'danger',
    ]


pipeline {
    agent any
    
    tools {
        terraform 'Terraform'
    }
    
    environment {
        AWS_ACCESS_KEY_ID     = credentials('jenkins-aws-secret-key-id')
        AWS_SECRET_ACCESS_KEY = credentials('jenkins-aws-secret-access-key')
    }

    stages {
        stage('Git Checkout') {
            steps {
                echo 'Cloning project code base into jenkins'
                git branch: 'main', credentialsId: 'git-token', url: 'https://github.com/iam-faith/airbnb-infra-repo.git'
                sh 'ls'
            }
        }
        
        stage('Terraform Version') {
            steps {
                echo 'Verifying terraform version'
                sh 'terraform --version'
            }
        }
        
        stage('Terraform Init') {
            steps {
                echo 'Initializing project'
                sh 'terraform init'
            }
        }
        
        stage('Terraform Plan') {
            steps {
                echo 'Running Terraform plan'
                sh 'terraform plan'
            }
        }         
     
     
        stage('Terraform Apply/Destroy') {
            steps {
                sh 'terraform ${action} --auto-approve'
            }
        } 
       
    }
    
    post { 
        always { 
            echo 'I will always say Hello again!'
            slackSend channel: '#jjtech-champions-devops-team', color: COLOR_MAP[currentBuild.currentResult], message: "*${currentBuild.currentResult}:* Job ${env.JOB_NAME} build ${env.BUILD_NUMBER} \n More info at: ${env.BUILD_URL}"
        }
        }    
    
}
def COLOR_MAP = [
    'SUCCESS': 'good',
    'FAILURE': 'danger',
    ]


pipeline {
    agent any
    
    tools {
        terraform 'Terraform'
    }
    
    environment {
        AWS_ACCESS_KEY_ID     = credentials('jenkins-aws-secret-key-id')
        AWS_SECRET_ACCESS_KEY = credentials('jenkins-aws-secret-access-key')
    }

    stages {
        stage('Git Checkout') {
            steps {
                echo 'Cloning project code base into jenkins'
                git branch: 'main', credentialsId: 'git-token', url: 'https://github.com/iam-faith/airbnb-infra-repo.git'
                sh 'ls'
            }
        }
        
        stage('Terraform Version') {
            steps {
                echo 'Verifying terraform version'
                sh 'terraform --version'
            }
        }
        
        stage('Terraform Init') {
            steps {
                echo 'Initializing project'
                sh 'terraform init'
            }
        }
        
        stage('Terraform Plan') {
            steps {
                echo 'Running Terraform plan'
                sh 'terraform plan'
            }
        }         
     
     
        stage('Terraform Apply/Destroy') {
            steps {
                sh 'terraform ${action} --auto-approve'
            }
        } 
       
    }
    
    post { 
        always { 
            echo 'I will always say Hello again!'
            slackSend channel: '#jjtech-champions-devops-team', color: COLOR_MAP[currentBuild.currentResult], message: "*${currentBuild.currentResult}:* Job ${env.JOB_NAME} build ${env.BUILD_NUMBER} \n More info at: ${env.BUILD_URL}"
        }
        }    
    
}
def COLOR_MAP = [
    'SUCCESS': 'good',
    'FAILURE': 'danger',
    ]


pipeline {
    agent any
    
    tools {
        terraform 'Terraform'
    }
    
    environment {
        AWS_ACCESS_KEY_ID     = credentials('jenkins-aws-secret-key-id')
        AWS_SECRET_ACCESS_KEY = credentials('jenkins-aws-secret-access-key')
    }

    stages {
        stage('Git Checkout') {
            steps {
                echo 'Cloning project code base into jenkins'
                git branch: 'main', credentialsId: 'git-token', url: 'https://github.com/iam-faith/airbnb-infra-repo.git'
                sh 'ls'
            }
        }
        
        stage('Terraform Version') {
            steps {
                echo 'Verifying terraform version'
                sh 'terraform --version'
            }
        }
        
        stage('Terraform Init') {
            steps {
                echo 'Initializing project'
                sh 'terraform init'
            }
        }
        
        stage('Terraform Plan') {
            steps {
                echo 'Running Terraform plan'
                sh 'terraform plan'
            }
        }         
     
     
        stage('Terraform Apply/Destroy') {
            steps {
                sh 'terraform ${action} --auto-approve'
            }
        } 
       
    }
    
    post { 
        always { 
            echo 'I will always say Hello again!'
            slackSend channel: '#jjtech-champions-devops-team', color: COLOR_MAP[currentBuild.currentResult], message: "*${currentBuild.currentResult}:* Job ${env.JOB_NAME} build ${env.BUILD_NUMBER} \n More info at: ${env.BUILD_URL}"
        }
        }    
    
}
def COLOR_MAP = [
    'SUCCESS': 'good',
    'FAILURE': 'danger',
    ]


pipeline {
    agent any
    
    tools {
        terraform 'Terraform'
    }
    
    environment {
        AWS_ACCESS_KEY_ID     = credentials('jenkins-aws-secret-key-id')
        AWS_SECRET_ACCESS_KEY = credentials('jenkins-aws-secret-access-key')
    }

    stages {
        stage('Git Checkout') {
            steps {
                echo 'Cloning project code base into jenkins'
                git branch: 'main', credentialsId: 'git-token', url: 'https://github.com/iam-faith/airbnb-infra-repo.git'
                sh 'ls'
            }
        }
        
        stage('Terraform Version') {
            steps {
                echo 'Verifying terraform version'
                sh 'terraform --version'
            }
        }
        
        stage('Terraform Init') {
            steps {
                echo 'Initializing project'
                sh 'terraform init'
            }
        }
        
        stage('Terraform Plan') {
            steps {
                echo 'Running Terraform plan'
                sh 'terraform plan'
            }
        }         
     
     
        stage('Terraform Apply/Destroy') {
            steps {
                sh 'terraform ${action} --auto-approve'
            }
        } 
       
    }
    
    post { 
        always { 
            echo 'I will always say Hello again!'
            slackSend channel: '#jjtech-champions-devops-team', color: COLOR_MAP[currentBuild.currentResult], message: "*${currentBuild.currentResult}:* Job ${env.JOB_NAME} build ${env.BUILD_NUMBER} \n More info at: ${env.BUILD_URL}"
        }
        }    
    
}
def COLOR_MAP = [
    'SUCCESS': 'good',
    'FAILURE': 'danger',
    ]


pipeline {
    agent any
    
    tools {
        terraform 'Terraform'
    }
    
    environment {
        AWS_ACCESS_KEY_ID     = credentials('jenkins-aws-secret-key-id')
        AWS_SECRET_ACCESS_KEY = credentials('jenkins-aws-secret-access-key')
    }

    stages {
        stage('Git Checkout') {
            steps {
                echo 'Cloning project code base into jenkins'
                git branch: 'main', credentialsId: 'git-token', url: 'https://github.com/iam-faith/airbnb-infra-repo.git'
                sh 'ls'
            }
        }
        
        stage('Terraform Version') {
            steps {
                echo 'Verifying terraform version'
                sh 'terraform --version'
            }
        }
        
        stage('Terraform Init') {
            steps {
                echo 'Initializing project'
                sh 'terraform init'
            }
        }
        
        stage('Terraform Plan') {
            steps {
                echo 'Running Terraform plan'
                sh 'terraform plan'
            }
        }         
     
     
        stage('Terraform Apply/Destroy') {
            steps {
                sh 'terraform ${action} --auto-approve'
            }
        } 
       
    }
    
    post { 
        always { 
            echo 'I will always say Hello again!'
            slackSend channel: '#jjtech-champions-devops-team', color: COLOR_MAP[currentBuild.currentResult], message: "*${currentBuild.currentResult}:* Job ${env.JOB_NAME} build ${env.BUILD_NUMBER} \n More info at: ${env.BUILD_URL}"
        }
        }    
    
}ject codebase....'
def COLOR_MAP = [
    'SUCCESS': 'good',
    'FAILURE': 'danger',
    ]


pipeline {
    agent any
    
    tools {
        terraform 'Terraform'
    }
    
    environment {
        AWS_ACCESS_KEY_ID     = credentials('jenkins-aws-secret-key-id')
        AWS_SECRET_ACCESS_KEY = credentials('jenkins-aws-secret-access-key')
    }

    stages {
        stage('Git Checkout') {
            steps {
                echo 'Cloning project code base into jenkins'
                git branch: 'main', credentialsId: 'git-token', url: 'https://github.com/iam-faith/airbnb-infra-repo.git'
                sh 'ls'
            }
        }
        
        stage('Terraform Version') {
            steps {
                echo 'Verifying terraform version'
                sh 'terraform --version'
            }
        }
        
        stage('Terraform Init') {
            steps {
                echo 'Initializing project'
                sh 'terraform init'
            }
        }
        
        stage('Terraform Plan') {
            steps {
                echo 'Running Terraform plan'
                sh 'terraform plan'
            }
        }         
     
     
        stage('Terraform Apply/Destroy') {
            steps {
                sh 'terraform ${action} --auto-approve'
            }
        } 
       
    }
    
    post { 
        always { 
            echo 'I will always say Hello again!'
            slackSend channel: '#jjtech-champions-devops-team', color: COLOR_MAP[currentBuild.currentResult], message: "*${currentBuild.currentResult}:* Job ${env.JOB_NAME} build ${env.BUILD_NUMBER} \n More info at: ${env.BUILD_URL}"
        }
        }    
    
}rl: 'https://github.com/iam-faith/airbnb-infra-repo.git'
def COLOR_MAP = [
    'SUCCESS': 'good',
    'FAILURE': 'danger',
    ]


pipeline {
    agent any
    
    tools {
        terraform 'Terraform'
    }
    
    environment {
        AWS_ACCESS_KEY_ID     = credentials('jenkins-aws-secret-key-id')
        AWS_SECRET_ACCESS_KEY = credentials('jenkins-aws-secret-access-key')
    }

    stages {
        stage('Git Checkout') {
            steps {
                echo 'Cloning project code base into jenkins'
                git branch: 'main', credentialsId: 'git-token', url: 'https://github.com/iam-faith/airbnb-infra-repo.git'
                sh 'ls'
            }
        }
        
        stage('Terraform Version') {
            steps {
                echo 'Verifying terraform version'
                sh 'terraform --version'
            }
        }
        
        stage('Terraform Init') {
            steps {
                echo 'Initializing project'
                sh 'terraform init'
            }
        }
        
        stage('Terraform Plan') {
            steps {
                echo 'Running Terraform plan'
                sh 'terraform plan'
            }
        }         
     
     
        stage('Terraform Apply/Destroy') {
            steps {
                sh 'terraform ${action} --auto-approve'
            }
        } 
       
    }
    
    post { 
        always { 
            echo 'I will always say Hello again!'
            slackSend channel: '#jjtech-champions-devops-team', color: COLOR_MAP[currentBuild.currentResult], message: "*${currentBuild.currentResult}:* Job ${env.JOB_NAME} build ${env.BUILD_NUMBER} \n More info at: ${env.BUILD_URL}"
        }
        }    
    
}
def COLOR_MAP = [
    'SUCCESS': 'good',
    'FAILURE': 'danger',
    ]


pipeline {
    agent any
    
    tools {
        terraform 'Terraform'
    }
    
    environment {
        AWS_ACCESS_KEY_ID     = credentials('jenkins-aws-secret-key-id')
        AWS_SECRET_ACCESS_KEY = credentials('jenkins-aws-secret-access-key')
    }

    stages {
        stage('Git Checkout') {
            steps {
                echo 'Cloning project code base into jenkins'
                git branch: 'main', credentialsId: 'git-token', url: 'https://github.com/iam-faith/airbnb-infra-repo.git'
                sh 'ls'
            }
        }
        
        stage('Terraform Version') {
            steps {
                echo 'Verifying terraform version'
                sh 'terraform --version'
            }
        }
        
        stage('Terraform Init') {
            steps {
                echo 'Initializing project'
                sh 'terraform init'
            }
        }
        
        stage('Terraform Plan') {
            steps {
                echo 'Running Terraform plan'
                sh 'terraform plan'
            }
        }         
     
     
        stage('Terraform Apply/Destroy') {
            steps {
                sh 'terraform ${action} --auto-approve'
            }
        } 
       
    }
    
    post { 
        always { 
            echo 'I will always say Hello again!'
            slackSend channel: '#jjtech-champions-devops-team', color: COLOR_MAP[currentBuild.currentResult], message: "*${currentBuild.currentResult}:* Job ${env.JOB_NAME} build ${env.BUILD_NUMBER} \n More info at: ${env.BUILD_URL}"
        }
        }    
    
}
def COLOR_MAP = [
    'SUCCESS': 'good',
    'FAILURE': 'danger',
    ]


pipeline {
    agent any
    
    tools {
        terraform 'Terraform'
    }
    
    environment {
        AWS_ACCESS_KEY_ID     = credentials('jenkins-aws-secret-key-id')
        AWS_SECRET_ACCESS_KEY = credentials('jenkins-aws-secret-access-key')
    }

    stages {
        stage('Git Checkout') {
            steps {
                echo 'Cloning project code base into jenkins'
                git branch: 'main', credentialsId: 'git-token', url: 'https://github.com/iam-faith/airbnb-infra-repo.git'
                sh 'ls'
            }
        }
        
        stage('Terraform Version') {
            steps {
                echo 'Verifying terraform version'
                sh 'terraform --version'
            }
        }
        
        stage('Terraform Init') {
            steps {
                echo 'Initializing project'
                sh 'terraform init'
            }
        }
        
        stage('Terraform Plan') {
            steps {
                echo 'Running Terraform plan'
                sh 'terraform plan'
            }
        }         
     
     
        stage('Terraform Apply/Destroy') {
            steps {
                sh 'terraform ${action} --auto-approve'
            }
        } 
       
    }
    
    post { 
        always { 
            echo 'I will always say Hello again!'
            slackSend channel: '#jjtech-champions-devops-team', color: COLOR_MAP[currentBuild.currentResult], message: "*${currentBuild.currentResult}:* Job ${env.JOB_NAME} build ${env.BUILD_NUMBER} \n More info at: ${env.BUILD_URL}"
        }
        }    
    
}
def COLOR_MAP = [
    'SUCCESS': 'good',
    'FAILURE': 'danger',
    ]


pipeline {
    agent any
    
    tools {
        terraform 'Terraform'
    }
    
    environment {
        AWS_ACCESS_KEY_ID     = credentials('jenkins-aws-secret-key-id')
        AWS_SECRET_ACCESS_KEY = credentials('jenkins-aws-secret-access-key')
    }

    stages {
        stage('Git Checkout') {
            steps {
                echo 'Cloning project code base into jenkins'
                git branch: 'main', credentialsId: 'git-token', url: 'https://github.com/iam-faith/airbnb-infra-repo.git'
                sh 'ls'
            }
        }
        
        stage('Terraform Version') {
            steps {
                echo 'Verifying terraform version'
                sh 'terraform --version'
            }
        }
        
        stage('Terraform Init') {
            steps {
                echo 'Initializing project'
                sh 'terraform init'
            }
        }
        
        stage('Terraform Plan') {
            steps {
                echo 'Running Terraform plan'
                sh 'terraform plan'
            }
        }         
     
     
        stage('Terraform Apply/Destroy') {
            steps {
                sh 'terraform ${action} --auto-approve'
            }
        } 
       
    }
    
    post { 
        always { 
            echo 'I will always say Hello again!'
            slackSend channel: '#jjtech-champions-devops-team', color: COLOR_MAP[currentBuild.currentResult], message: "*${currentBuild.currentResult}:* Job ${env.JOB_NAME} build ${env.BUILD_NUMBER} \n More info at: ${env.BUILD_URL}"
        }
        }    
    
}
def COLOR_MAP = [
    'SUCCESS': 'good',
    'FAILURE': 'danger',
    ]


pipeline {
    agent any
    
    tools {
        terraform 'Terraform'
    }
    
    environment {
        AWS_ACCESS_KEY_ID     = credentials('jenkins-aws-secret-key-id')
        AWS_SECRET_ACCESS_KEY = credentials('jenkins-aws-secret-access-key')
    }

    stages {
        stage('Git Checkout') {
            steps {
                echo 'Cloning project code base into jenkins'
                git branch: 'main', credentialsId: 'git-token', url: 'https://github.com/iam-faith/airbnb-infra-repo.git'
                sh 'ls'
            }
        }
        
        stage('Terraform Version') {
            steps {
                echo 'Verifying terraform version'
                sh 'terraform --version'
            }
        }
        
        stage('Terraform Init') {
            steps {
                echo 'Initializing project'
                sh 'terraform init'
            }
        }
        
        stage('Terraform Plan') {
            steps {
                echo 'Running Terraform plan'
                sh 'terraform plan'
            }
        }         
     
     
        stage('Terraform Apply/Destroy') {
            steps {
                sh 'terraform ${action} --auto-approve'
            }
        } 
       
    }
    
    post { 
        always { 
            echo 'I will always say Hello again!'
            slackSend channel: '#jjtech-champions-devops-team', color: COLOR_MAP[currentBuild.currentResult], message: "*${currentBuild.currentResult}:* Job ${env.JOB_NAME} build ${env.BUILD_NUMBER} \n More info at: ${env.BUILD_URL}"
        }
        }    
    
}
def COLOR_MAP = [
    'SUCCESS': 'good',
    'FAILURE': 'danger',
    ]


pipeline {
    agent any
    
    tools {
        terraform 'Terraform'
    }
    
    environment {
        AWS_ACCESS_KEY_ID     = credentials('jenkins-aws-secret-key-id')
        AWS_SECRET_ACCESS_KEY = credentials('jenkins-aws-secret-access-key')
    }

    stages {
        stage('Git Checkout') {
            steps {
                echo 'Cloning project code base into jenkins'
                git branch: 'main', credentialsId: 'git-token', url: 'https://github.com/iam-faith/airbnb-infra-repo.git'
                sh 'ls'
            }
        }
        
        stage('Terraform Version') {
            steps {
                echo 'Verifying terraform version'
                sh 'terraform --version'
            }
        }
        
        stage('Terraform Init') {
            steps {
                echo 'Initializing project'
                sh 'terraform init'
            }
        }
        
        stage('Terraform Plan') {
            steps {
                echo 'Running Terraform plan'
                sh 'terraform plan'
            }
        }         
     
     
        stage('Terraform Apply/Destroy') {
            steps {
                sh 'terraform ${action} --auto-approve'
            }
        } 
       
    }
    
    post { 
        always { 
            echo 'I will always say Hello again!'
            slackSend channel: '#jjtech-champions-devops-team', color: COLOR_MAP[currentBuild.currentResult], message: "*${currentBuild.currentResult}:* Job ${env.JOB_NAME} build ${env.BUILD_NUMBER} \n More info at: ${env.BUILD_URL}"
        }
        }    
    
}
def COLOR_MAP = [
    'SUCCESS': 'good',
    'FAILURE': 'danger',
    ]


pipeline {
    agent any
    
    tools {
        terraform 'Terraform'
    }
    
    environment {
        AWS_ACCESS_KEY_ID     = credentials('jenkins-aws-secret-key-id')
        AWS_SECRET_ACCESS_KEY = credentials('jenkins-aws-secret-access-key')
    }

    stages {
        stage('Git Checkout') {
            steps {
                echo 'Cloning project code base into jenkins'
                git branch: 'main', credentialsId: 'git-token', url: 'https://github.com/iam-faith/airbnb-infra-repo.git'
                sh 'ls'
            }
        }
        
        stage('Terraform Version') {
            steps {
                echo 'Verifying terraform version'
                sh 'terraform --version'
            }
        }
        
        stage('Terraform Init') {
            steps {
                echo 'Initializing project'
                sh 'terraform init'
            }
        }
        
        stage('Terraform Plan') {
            steps {
                echo 'Running Terraform plan'
                sh 'terraform plan'
            }
        }         
     
     
        stage('Terraform Apply/Destroy') {
            steps {
                sh 'terraform ${action} --auto-approve'
            }
        } 
       
    }
    
    post { 
        always { 
            echo 'I will always say Hello again!'
            slackSend channel: '#jjtech-champions-devops-team', color: COLOR_MAP[currentBuild.currentResult], message: "*${currentBuild.currentResult}:* Job ${env.JOB_NAME} build ${env.BUILD_NUMBER} \n More info at: ${env.BUILD_URL}"
        }
        }    
    
}
def COLOR_MAP = [
    'SUCCESS': 'good',
    'FAILURE': 'danger',
    ]


pipeline {
    agent any
    
    tools {
        terraform 'Terraform'
    }
    
    environment {
        AWS_ACCESS_KEY_ID     = credentials('jenkins-aws-secret-key-id')
        AWS_SECRET_ACCESS_KEY = credentials('jenkins-aws-secret-access-key')
    }

    stages {
        stage('Git Checkout') {
            steps {
                echo 'Cloning project code base into jenkins'
                git branch: 'main', credentialsId: 'git-token', url: 'https://github.com/iam-faith/airbnb-infra-repo.git'
                sh 'ls'
            }
        }
        
        stage('Terraform Version') {
            steps {
                echo 'Verifying terraform version'
                sh 'terraform --version'
            }
        }
        
        stage('Terraform Init') {
            steps {
                echo 'Initializing project'
                sh 'terraform init'
            }
        }
        
        stage('Terraform Plan') {
            steps {
                echo 'Running Terraform plan'
                sh 'terraform plan'
            }
        }         
     
     
        stage('Terraform Apply/Destroy') {
            steps {
                sh 'terraform ${action} --auto-approve'
            }
        } 
       
    }
    
    post { 
        always { 
            echo 'I will always say Hello again!'
            slackSend channel: '#jjtech-champions-devops-team', color: COLOR_MAP[currentBuild.currentResult], message: "*${currentBuild.currentResult}:* Job ${env.JOB_NAME} build ${env.BUILD_NUMBER} \n More info at: ${env.BUILD_URL}"
        }
        }    
    
}
def COLOR_MAP = [
    'SUCCESS': 'good',
    'FAILURE': 'danger',
    ]


pipeline {
    agent any
    
    tools {
        terraform 'Terraform'
    }
    
    environment {
        AWS_ACCESS_KEY_ID     = credentials('jenkins-aws-secret-key-id')
        AWS_SECRET_ACCESS_KEY = credentials('jenkins-aws-secret-access-key')
    }

    stages {
        stage('Git Checkout') {
            steps {
                echo 'Cloning project code base into jenkins'
                git branch: 'main', credentialsId: 'git-token', url: 'https://github.com/iam-faith/airbnb-infra-repo.git'
                sh 'ls'
            }
        }
        
        stage('Terraform Version') {
            steps {
                echo 'Verifying terraform version'
                sh 'terraform --version'
            }
        }
        
        stage('Terraform Init') {
            steps {
                echo 'Initializing project'
                sh 'terraform init'
            }
        }
        
        stage('Terraform Plan') {
            steps {
                echo 'Running Terraform plan'
                sh 'terraform plan'
            }
        }         
     
     
        stage('Terraform Apply/Destroy') {
            steps {
                sh 'terraform ${action} --auto-approve'
            }
        } 
       
    }
    
    post { 
        always { 
            echo 'I will always say Hello again!'
            slackSend channel: '#jjtech-champions-devops-team', color: COLOR_MAP[currentBuild.currentResult], message: "*${currentBuild.currentResult}:* Job ${env.JOB_NAME} build ${env.BUILD_NUMBER} \n More info at: ${env.BUILD_URL}"
        }
        }    
    
}...'
def COLOR_MAP = [
    'SUCCESS': 'good',
    'FAILURE': 'danger',
    ]


pipeline {
    agent any
    
    tools {
        terraform 'Terraform'
    }
    
    environment {
        AWS_ACCESS_KEY_ID     = credentials('jenkins-aws-secret-key-id')
        AWS_SECRET_ACCESS_KEY = credentials('jenkins-aws-secret-access-key')
    }

    stages {
        stage('Git Checkout') {
            steps {
                echo 'Cloning project code base into jenkins'
                git branch: 'main', credentialsId: 'git-token', url: 'https://github.com/iam-faith/airbnb-infra-repo.git'
                sh 'ls'
            }
        }
        
        stage('Terraform Version') {
            steps {
                echo 'Verifying terraform version'
                sh 'terraform --version'
            }
        }
        
        stage('Terraform Init') {
            steps {
                echo 'Initializing project'
                sh 'terraform init'
            }
        }
        
        stage('Terraform Plan') {
            steps {
                echo 'Running Terraform plan'
                sh 'terraform plan'
            }
        }         
     
     
        stage('Terraform Apply/Destroy') {
            steps {
                sh 'terraform ${action} --auto-approve'
            }
        } 
       
    }
    
    post { 
        always { 
            echo 'I will always say Hello again!'
            slackSend channel: '#jjtech-champions-devops-team', color: COLOR_MAP[currentBuild.currentResult], message: "*${currentBuild.currentResult}:* Job ${env.JOB_NAME} build ${env.BUILD_NUMBER} \n More info at: ${env.BUILD_URL}"
        }
        }    
    
}
def COLOR_MAP = [
    'SUCCESS': 'good',
    'FAILURE': 'danger',
    ]


pipeline {
    agent any
    
    tools {
        terraform 'Terraform'
    }
    
    environment {
        AWS_ACCESS_KEY_ID     = credentials('jenkins-aws-secret-key-id')
        AWS_SECRET_ACCESS_KEY = credentials('jenkins-aws-secret-access-key')
    }

    stages {
        stage('Git Checkout') {
            steps {
                echo 'Cloning project code base into jenkins'
                git branch: 'main', credentialsId: 'git-token', url: 'https://github.com/iam-faith/airbnb-infra-repo.git'
                sh 'ls'
            }
        }
        
        stage('Terraform Version') {
            steps {
                echo 'Verifying terraform version'
                sh 'terraform --version'
            }
        }
        
        stage('Terraform Init') {
            steps {
                echo 'Initializing project'
                sh 'terraform init'
            }
        }
        
        stage('Terraform Plan') {
            steps {
                echo 'Running Terraform plan'
                sh 'terraform plan'
            }
        }         
     
     
        stage('Terraform Apply/Destroy') {
            steps {
                sh 'terraform ${action} --auto-approve'
            }
        } 
       
    }
    
    post { 
        always { 
            echo 'I will always say Hello again!'
            slackSend channel: '#jjtech-champions-devops-team', color: COLOR_MAP[currentBuild.currentResult], message: "*${currentBuild.currentResult}:* Job ${env.JOB_NAME} build ${env.BUILD_NUMBER} \n More info at: ${env.BUILD_URL}"
        }
        }    
    
}
def COLOR_MAP = [
    'SUCCESS': 'good',
    'FAILURE': 'danger',
    ]


pipeline {
    agent any
    
    tools {
        terraform 'Terraform'
    }
    
    environment {
        AWS_ACCESS_KEY_ID     = credentials('jenkins-aws-secret-key-id')
        AWS_SECRET_ACCESS_KEY = credentials('jenkins-aws-secret-access-key')
    }

    stages {
        stage('Git Checkout') {
            steps {
                echo 'Cloning project code base into jenkins'
                git branch: 'main', credentialsId: 'git-token', url: 'https://github.com/iam-faith/airbnb-infra-repo.git'
                sh 'ls'
            }
        }
        
        stage('Terraform Version') {
            steps {
                echo 'Verifying terraform version'
                sh 'terraform --version'
            }
        }
        
        stage('Terraform Init') {
            steps {
                echo 'Initializing project'
                sh 'terraform init'
            }
        }
        
        stage('Terraform Plan') {
            steps {
                echo 'Running Terraform plan'
                sh 'terraform plan'
            }
        }         
     
     
        stage('Terraform Apply/Destroy') {
            steps {
                sh 'terraform ${action} --auto-approve'
            }
        } 
       
    }
    
    post { 
        always { 
            echo 'I will always say Hello again!'
            slackSend channel: '#jjtech-champions-devops-team', color: COLOR_MAP[currentBuild.currentResult], message: "*${currentBuild.currentResult}:* Job ${env.JOB_NAME} build ${env.BUILD_NUMBER} \n More info at: ${env.BUILD_URL}"
        }
        }    
    
}
def COLOR_MAP = [
    'SUCCESS': 'good',
    'FAILURE': 'danger',
    ]


pipeline {
    agent any
    
    tools {
        terraform 'Terraform'
    }
    
    environment {
        AWS_ACCESS_KEY_ID     = credentials('jenkins-aws-secret-key-id')
        AWS_SECRET_ACCESS_KEY = credentials('jenkins-aws-secret-access-key')
    }

    stages {
        stage('Git Checkout') {
            steps {
                echo 'Cloning project code base into jenkins'
                git branch: 'main', credentialsId: 'git-token', url: 'https://github.com/iam-faith/airbnb-infra-repo.git'
                sh 'ls'
            }
        }
        
        stage('Terraform Version') {
            steps {
                echo 'Verifying terraform version'
                sh 'terraform --version'
            }
        }
        
        stage('Terraform Init') {
            steps {
                echo 'Initializing project'
                sh 'terraform init'
            }
        }
        
        stage('Terraform Plan') {
            steps {
                echo 'Running Terraform plan'
                sh 'terraform plan'
            }
        }         
     
     
        stage('Terraform Apply/Destroy') {
            steps {
                sh 'terraform ${action} --auto-approve'
            }
        } 
       
    }
    
    post { 
        always { 
            echo 'I will always say Hello again!'
            slackSend channel: '#jjtech-champions-devops-team', color: COLOR_MAP[currentBuild.currentResult], message: "*${currentBuild.currentResult}:* Job ${env.JOB_NAME} build ${env.BUILD_NUMBER} \n More info at: ${env.BUILD_URL}"
        }
        }    
    
}
def COLOR_MAP = [
    'SUCCESS': 'good',
    'FAILURE': 'danger',
    ]


pipeline {
    agent any
    
    tools {
        terraform 'Terraform'
    }
    
    environment {
        AWS_ACCESS_KEY_ID     = credentials('jenkins-aws-secret-key-id')
        AWS_SECRET_ACCESS_KEY = credentials('jenkins-aws-secret-access-key')
    }

    stages {
        stage('Git Checkout') {
            steps {
                echo 'Cloning project code base into jenkins'
                git branch: 'main', credentialsId: 'git-token', url: 'https://github.com/iam-faith/airbnb-infra-repo.git'
                sh 'ls'
            }
        }
        
        stage('Terraform Version') {
            steps {
                echo 'Verifying terraform version'
                sh 'terraform --version'
            }
        }
        
        stage('Terraform Init') {
            steps {
                echo 'Initializing project'
                sh 'terraform init'
            }
        }
        
        stage('Terraform Plan') {
            steps {
                echo 'Running Terraform plan'
                sh 'terraform plan'
            }
        }         
     
     
        stage('Terraform Apply/Destroy') {
            steps {
                sh 'terraform ${action} --auto-approve'
            }
        } 
       
    }
    
    post { 
        always { 
            echo 'I will always say Hello again!'
            slackSend channel: '#jjtech-champions-devops-team', color: COLOR_MAP[currentBuild.currentResult], message: "*${currentBuild.currentResult}:* Job ${env.JOB_NAME} build ${env.BUILD_NUMBER} \n More info at: ${env.BUILD_URL}"
        }
        }    
    
}
def COLOR_MAP = [
    'SUCCESS': 'good',
    'FAILURE': 'danger',
    ]


pipeline {
    agent any
    
    tools {
        terraform 'Terraform'
    }
    
    environment {
        AWS_ACCESS_KEY_ID     = credentials('jenkins-aws-secret-key-id')
        AWS_SECRET_ACCESS_KEY = credentials('jenkins-aws-secret-access-key')
    }

    stages {
        stage('Git Checkout') {
            steps {
                echo 'Cloning project code base into jenkins'
                git branch: 'main', credentialsId: 'git-token', url: 'https://github.com/iam-faith/airbnb-infra-repo.git'
                sh 'ls'
            }
        }
        
        stage('Terraform Version') {
            steps {
                echo 'Verifying terraform version'
                sh 'terraform --version'
            }
        }
        
        stage('Terraform Init') {
            steps {
                echo 'Initializing project'
                sh 'terraform init'
            }
        }
        
        stage('Terraform Plan') {
            steps {
                echo 'Running Terraform plan'
                sh 'terraform plan'
            }
        }         
     
     
        stage('Terraform Apply/Destroy') {
            steps {
                sh 'terraform ${action} --auto-approve'
            }
        } 
       
    }
    
    post { 
        always { 
            echo 'I will always say Hello again!'
            slackSend channel: '#jjtech-champions-devops-team', color: COLOR_MAP[currentBuild.currentResult], message: "*${currentBuild.currentResult}:* Job ${env.JOB_NAME} build ${env.BUILD_NUMBER} \n More info at: ${env.BUILD_URL}"
        }
        }    
    
}
def COLOR_MAP = [
    'SUCCESS': 'good',
    'FAILURE': 'danger',
    ]


pipeline {
    agent any
    
    tools {
        terraform 'Terraform'
    }
    
    environment {
        AWS_ACCESS_KEY_ID     = credentials('jenkins-aws-secret-key-id')
        AWS_SECRET_ACCESS_KEY = credentials('jenkins-aws-secret-access-key')
    }

    stages {
        stage('Git Checkout') {
            steps {
                echo 'Cloning project code base into jenkins'
                git branch: 'main', credentialsId: 'git-token', url: 'https://github.com/iam-faith/airbnb-infra-repo.git'
                sh 'ls'
            }
        }
        
        stage('Terraform Version') {
            steps {
                echo 'Verifying terraform version'
                sh 'terraform --version'
            }
        }
        
        stage('Terraform Init') {
            steps {
                echo 'Initializing project'
                sh 'terraform init'
            }
        }
        
        stage('Terraform Plan') {
            steps {
                echo 'Running Terraform plan'
                sh 'terraform plan'
            }
        }         
     
     
        stage('Terraform Apply/Destroy') {
            steps {
                sh 'terraform ${action} --auto-approve'
            }
        } 
       
    }
    
    post { 
        always { 
            echo 'I will always say Hello again!'
            slackSend channel: '#jjtech-champions-devops-team', color: COLOR_MAP[currentBuild.currentResult], message: "*${currentBuild.currentResult}:* Job ${env.JOB_NAME} build ${env.BUILD_NUMBER} \n More info at: ${env.BUILD_URL}"
        }
        }    
    
}
def COLOR_MAP = [
    'SUCCESS': 'good',
    'FAILURE': 'danger',
    ]


pipeline {
    agent any
    
    tools {
        terraform 'Terraform'
    }
    
    environment {
        AWS_ACCESS_KEY_ID     = credentials('jenkins-aws-secret-key-id')
        AWS_SECRET_ACCESS_KEY = credentials('jenkins-aws-secret-access-key')
    }

    stages {
        stage('Git Checkout') {
            steps {
                echo 'Cloning project code base into jenkins'
                git branch: 'main', credentialsId: 'git-token', url: 'https://github.com/iam-faith/airbnb-infra-repo.git'
                sh 'ls'
            }
        }
        
        stage('Terraform Version') {
            steps {
                echo 'Verifying terraform version'
                sh 'terraform --version'
            }
        }
        
        stage('Terraform Init') {
            steps {
                echo 'Initializing project'
                sh 'terraform init'
            }
        }
        
        stage('Terraform Plan') {
            steps {
                echo 'Running Terraform plan'
                sh 'terraform plan'
            }
        }         
     
     
        stage('Terraform Apply/Destroy') {
            steps {
                sh 'terraform ${action} --auto-approve'
            }
        } 
       
    }
    
    post { 
        always { 
            echo 'I will always say Hello again!'
            slackSend channel: '#jjtech-champions-devops-team', color: COLOR_MAP[currentBuild.currentResult], message: "*${currentBuild.currentResult}:* Job ${env.JOB_NAME} build ${env.BUILD_NUMBER} \n More info at: ${env.BUILD_URL}"
        }
        }    
    
}
def COLOR_MAP = [
    'SUCCESS': 'good',
    'FAILURE': 'danger',
    ]


pipeline {
    agent any
    
    tools {
        terraform 'Terraform'
    }
    
    environment {
        AWS_ACCESS_KEY_ID     = credentials('jenkins-aws-secret-key-id')
        AWS_SECRET_ACCESS_KEY = credentials('jenkins-aws-secret-access-key')
    }

    stages {
        stage('Git Checkout') {
            steps {
                echo 'Cloning project code base into jenkins'
                git branch: 'main', credentialsId: 'git-token', url: 'https://github.com/iam-faith/airbnb-infra-repo.git'
                sh 'ls'
            }
        }
        
        stage('Terraform Version') {
            steps {
                echo 'Verifying terraform version'
                sh 'terraform --version'
            }
        }
        
        stage('Terraform Init') {
            steps {
                echo 'Initializing project'
                sh 'terraform init'
            }
        }
        
        stage('Terraform Plan') {
            steps {
                echo 'Running Terraform plan'
                sh 'terraform plan'
            }
        }         
     
     
        stage('Terraform Apply/Destroy') {
            steps {
                sh 'terraform ${action} --auto-approve'
            }
        } 
       
    }
    
    post { 
        always { 
            echo 'I will always say Hello again!'
            slackSend channel: '#jjtech-champions-devops-team', color: COLOR_MAP[currentBuild.currentResult], message: "*${currentBuild.currentResult}:* Job ${env.JOB_NAME} build ${env.BUILD_NUMBER} \n More info at: ${env.BUILD_URL}"
        }
        }    
    
}
def COLOR_MAP = [
    'SUCCESS': 'good',
    'FAILURE': 'danger',
    ]


pipeline {
    agent any
    
    tools {
        terraform 'Terraform'
    }
    
    environment {
        AWS_ACCESS_KEY_ID     = credentials('jenkins-aws-secret-key-id')
        AWS_SECRET_ACCESS_KEY = credentials('jenkins-aws-secret-access-key')
    }

    stages {
        stage('Git Checkout') {
            steps {
                echo 'Cloning project code base into jenkins'
                git branch: 'main', credentialsId: 'git-token', url: 'https://github.com/iam-faith/airbnb-infra-repo.git'
                sh 'ls'
            }
        }
        
        stage('Terraform Version') {
            steps {
                echo 'Verifying terraform version'
                sh 'terraform --version'
            }
        }
        
        stage('Terraform Init') {
            steps {
                echo 'Initializing project'
                sh 'terraform init'
            }
        }
        
        stage('Terraform Plan') {
            steps {
                echo 'Running Terraform plan'
                sh 'terraform plan'
            }
        }         
     
     
        stage('Terraform Apply/Destroy') {
            steps {
                sh 'terraform ${action} --auto-approve'
            }
        } 
       
    }
    
    post { 
        always { 
            echo 'I will always say Hello again!'
            slackSend channel: '#jjtech-champions-devops-team', color: COLOR_MAP[currentBuild.currentResult], message: "*${currentBuild.currentResult}:* Job ${env.JOB_NAME} build ${env.BUILD_NUMBER} \n More info at: ${env.BUILD_URL}"
        }
        }    
    
}e'
def COLOR_MAP = [
    'SUCCESS': 'good',
    'FAILURE': 'danger',
    ]


pipeline {
    agent any
    
    tools {
        terraform 'Terraform'
    }
    
    environment {
        AWS_ACCESS_KEY_ID     = credentials('jenkins-aws-secret-key-id')
        AWS_SECRET_ACCESS_KEY = credentials('jenkins-aws-secret-access-key')
    }

    stages {
        stage('Git Checkout') {
            steps {
                echo 'Cloning project code base into jenkins'
                git branch: 'main', credentialsId: 'git-token', url: 'https://github.com/iam-faith/airbnb-infra-repo.git'
                sh 'ls'
            }
        }
        
        stage('Terraform Version') {
            steps {
                echo 'Verifying terraform version'
                sh 'terraform --version'
            }
        }
        
        stage('Terraform Init') {
            steps {
                echo 'Initializing project'
                sh 'terraform init'
            }
        }
        
        stage('Terraform Plan') {
            steps {
                echo 'Running Terraform plan'
                sh 'terraform plan'
            }
        }         
     
     
        stage('Terraform Apply/Destroy') {
            steps {
                sh 'terraform ${action} --auto-approve'
            }
        } 
       
    }
    
    post { 
        always { 
            echo 'I will always say Hello again!'
            slackSend channel: '#jjtech-champions-devops-team', color: COLOR_MAP[currentBuild.currentResult], message: "*${currentBuild.currentResult}:* Job ${env.JOB_NAME} build ${env.BUILD_NUMBER} \n More info at: ${env.BUILD_URL}"
        }
        }    
    
}
def COLOR_MAP = [
    'SUCCESS': 'good',
    'FAILURE': 'danger',
    ]


pipeline {
    agent any
    
    tools {
        terraform 'Terraform'
    }
    
    environment {
        AWS_ACCESS_KEY_ID     = credentials('jenkins-aws-secret-key-id')
        AWS_SECRET_ACCESS_KEY = credentials('jenkins-aws-secret-access-key')
    }

    stages {
        stage('Git Checkout') {
            steps {
                echo 'Cloning project code base into jenkins'
                git branch: 'main', credentialsId: 'git-token', url: 'https://github.com/iam-faith/airbnb-infra-repo.git'
                sh 'ls'
            }
        }
        
        stage('Terraform Version') {
            steps {
                echo 'Verifying terraform version'
                sh 'terraform --version'
            }
        }
        
        stage('Terraform Init') {
            steps {
                echo 'Initializing project'
                sh 'terraform init'
            }
        }
        
        stage('Terraform Plan') {
            steps {
                echo 'Running Terraform plan'
                sh 'terraform plan'
            }
        }         
     
     
        stage('Terraform Apply/Destroy') {
            steps {
                sh 'terraform ${action} --auto-approve'
            }
        } 
       
    }
    
    post { 
        always { 
            echo 'I will always say Hello again!'
            slackSend channel: '#jjtech-champions-devops-team', color: COLOR_MAP[currentBuild.currentResult], message: "*${currentBuild.currentResult}:* Job ${env.JOB_NAME} build ${env.BUILD_NUMBER} \n More info at: ${env.BUILD_URL}"
        }
        }    
    
}
def COLOR_MAP = [
    'SUCCESS': 'good',
    'FAILURE': 'danger',
    ]


pipeline {
    agent any
    
    tools {
        terraform 'Terraform'
    }
    
    environment {
        AWS_ACCESS_KEY_ID     = credentials('jenkins-aws-secret-key-id')
        AWS_SECRET_ACCESS_KEY = credentials('jenkins-aws-secret-access-key')
    }

    stages {
        stage('Git Checkout') {
            steps {
                echo 'Cloning project code base into jenkins'
                git branch: 'main', credentialsId: 'git-token', url: 'https://github.com/iam-faith/airbnb-infra-repo.git'
                sh 'ls'
            }
        }
        
        stage('Terraform Version') {
            steps {
                echo 'Verifying terraform version'
                sh 'terraform --version'
            }
        }
        
        stage('Terraform Init') {
            steps {
                echo 'Initializing project'
                sh 'terraform init'
            }
        }
        
        stage('Terraform Plan') {
            steps {
                echo 'Running Terraform plan'
                sh 'terraform plan'
            }
        }         
     
     
        stage('Terraform Apply/Destroy') {
            steps {
                sh 'terraform ${action} --auto-approve'
            }
        } 
       
    }
    
    post { 
        always { 
            echo 'I will always say Hello again!'
            slackSend channel: '#jjtech-champions-devops-team', color: COLOR_MAP[currentBuild.currentResult], message: "*${currentBuild.currentResult}:* Job ${env.JOB_NAME} build ${env.BUILD_NUMBER} \n More info at: ${env.BUILD_URL}"
        }
        }    
    
}
def COLOR_MAP = [
    'SUCCESS': 'good',
    'FAILURE': 'danger',
    ]


pipeline {
    agent any
    
    tools {
        terraform 'Terraform'
    }
    
    environment {
        AWS_ACCESS_KEY_ID     = credentials('jenkins-aws-secret-key-id')
        AWS_SECRET_ACCESS_KEY = credentials('jenkins-aws-secret-access-key')
    }

    stages {
        stage('Git Checkout') {
            steps {
                echo 'Cloning project code base into jenkins'
                git branch: 'main', credentialsId: 'git-token', url: 'https://github.com/iam-faith/airbnb-infra-repo.git'
                sh 'ls'
            }
        }
        
        stage('Terraform Version') {
            steps {
                echo 'Verifying terraform version'
                sh 'terraform --version'
            }
        }
        
        stage('Terraform Init') {
            steps {
                echo 'Initializing project'
                sh 'terraform init'
            }
        }
        
        stage('Terraform Plan') {
            steps {
                echo 'Running Terraform plan'
                sh 'terraform plan'
            }
        }         
     
     
        stage('Terraform Apply/Destroy') {
            steps {
                sh 'terraform ${action} --auto-approve'
            }
        } 
       
    }
    
    post { 
        always { 
            echo 'I will always say Hello again!'
            slackSend channel: '#jjtech-champions-devops-team', color: COLOR_MAP[currentBuild.currentResult], message: "*${currentBuild.currentResult}:* Job ${env.JOB_NAME} build ${env.BUILD_NUMBER} \n More info at: ${env.BUILD_URL}"
        }
        }    
    
}
def COLOR_MAP = [
    'SUCCESS': 'good',
    'FAILURE': 'danger',
    ]


pipeline {
    agent any
    
    tools {
        terraform 'Terraform'
    }
    
    environment {
        AWS_ACCESS_KEY_ID     = credentials('jenkins-aws-secret-key-id')
        AWS_SECRET_ACCESS_KEY = credentials('jenkins-aws-secret-access-key')
    }

    stages {
        stage('Git Checkout') {
            steps {
                echo 'Cloning project code base into jenkins'
                git branch: 'main', credentialsId: 'git-token', url: 'https://github.com/iam-faith/airbnb-infra-repo.git'
                sh 'ls'
            }
        }
        
        stage('Terraform Version') {
            steps {
                echo 'Verifying terraform version'
                sh 'terraform --version'
            }
        }
        
        stage('Terraform Init') {
            steps {
                echo 'Initializing project'
                sh 'terraform init'
            }
        }
        
        stage('Terraform Plan') {
            steps {
                echo 'Running Terraform plan'
                sh 'terraform plan'
            }
        }         
     
     
        stage('Terraform Apply/Destroy') {
            steps {
                sh 'terraform ${action} --auto-approve'
            }
        } 
       
    }
    
    post { 
        always { 
            echo 'I will always say Hello again!'
            slackSend channel: '#jjtech-champions-devops-team', color: COLOR_MAP[currentBuild.currentResult], message: "*${currentBuild.currentResult}:* Job ${env.JOB_NAME} build ${env.BUILD_NUMBER} \n More info at: ${env.BUILD_URL}"
        }
        }    
    
}
def COLOR_MAP = [
    'SUCCESS': 'good',
    'FAILURE': 'danger',
    ]


pipeline {
    agent any
    
    tools {
        terraform 'Terraform'
    }
    
    environment {
        AWS_ACCESS_KEY_ID     = credentials('jenkins-aws-secret-key-id')
        AWS_SECRET_ACCESS_KEY = credentials('jenkins-aws-secret-access-key')
    }

    stages {
        stage('Git Checkout') {
            steps {
                echo 'Cloning project code base into jenkins'
                git branch: 'main', credentialsId: 'git-token', url: 'https://github.com/iam-faith/airbnb-infra-repo.git'
                sh 'ls'
            }
        }
        
        stage('Terraform Version') {
            steps {
                echo 'Verifying terraform version'
                sh 'terraform --version'
            }
        }
        
        stage('Terraform Init') {
            steps {
                echo 'Initializing project'
                sh 'terraform init'
            }
        }
        
        stage('Terraform Plan') {
            steps {
                echo 'Running Terraform plan'
                sh 'terraform plan'
            }
        }         
     
     
        stage('Terraform Apply/Destroy') {
            steps {
                sh 'terraform ${action} --auto-approve'
            }
        } 
       
    }
    
    post { 
        always { 
            echo 'I will always say Hello again!'
            slackSend channel: '#jjtech-champions-devops-team', color: COLOR_MAP[currentBuild.currentResult], message: "*${currentBuild.currentResult}:* Job ${env.JOB_NAME} build ${env.BUILD_NUMBER} \n More info at: ${env.BUILD_URL}"
        }
        }    
    
}
def COLOR_MAP = [
    'SUCCESS': 'good',
    'FAILURE': 'danger',
    ]


pipeline {
    agent any
    
    tools {
        terraform 'Terraform'
    }
    
    environment {
        AWS_ACCESS_KEY_ID     = credentials('jenkins-aws-secret-key-id')
        AWS_SECRET_ACCESS_KEY = credentials('jenkins-aws-secret-access-key')
    }

    stages {
        stage('Git Checkout') {
            steps {
                echo 'Cloning project code base into jenkins'
                git branch: 'main', credentialsId: 'git-token', url: 'https://github.com/iam-faith/airbnb-infra-repo.git'
                sh 'ls'
            }
        }
        
        stage('Terraform Version') {
            steps {
                echo 'Verifying terraform version'
                sh 'terraform --version'
            }
        }
        
        stage('Terraform Init') {
            steps {
                echo 'Initializing project'
                sh 'terraform init'
            }
        }
        
        stage('Terraform Plan') {
            steps {
                echo 'Running Terraform plan'
                sh 'terraform plan'
            }
        }         
     
     
        stage('Terraform Apply/Destroy') {
            steps {
                sh 'terraform ${action} --auto-approve'
            }
        } 
       
    }
    
    post { 
        always { 
            echo 'I will always say Hello again!'
            slackSend channel: '#jjtech-champions-devops-team', color: COLOR_MAP[currentBuild.currentResult], message: "*${currentBuild.currentResult}:* Job ${env.JOB_NAME} build ${env.BUILD_NUMBER} \n More info at: ${env.BUILD_URL}"
        }
        }    
    
}
def COLOR_MAP = [
    'SUCCESS': 'good',
    'FAILURE': 'danger',
    ]


pipeline {
    agent any
    
    tools {
        terraform 'Terraform'
    }
    
    environment {
        AWS_ACCESS_KEY_ID     = credentials('jenkins-aws-secret-key-id')
        AWS_SECRET_ACCESS_KEY = credentials('jenkins-aws-secret-access-key')
    }

    stages {
        stage('Git Checkout') {
            steps {
                echo 'Cloning project code base into jenkins'
                git branch: 'main', credentialsId: 'git-token', url: 'https://github.com/iam-faith/airbnb-infra-repo.git'
                sh 'ls'
            }
        }
        
        stage('Terraform Version') {
            steps {
                echo 'Verifying terraform version'
                sh 'terraform --version'
            }
        }
        
        stage('Terraform Init') {
            steps {
                echo 'Initializing project'
                sh 'terraform init'
            }
        }
        
        stage('Terraform Plan') {
            steps {
                echo 'Running Terraform plan'
                sh 'terraform plan'
            }
        }         
     
     
        stage('Terraform Apply/Destroy') {
            steps {
                sh 'terraform ${action} --auto-approve'
            }
        } 
       
    }
    
    post { 
        always { 
            echo 'I will always say Hello again!'
            slackSend channel: '#jjtech-champions-devops-team', color: COLOR_MAP[currentBuild.currentResult], message: "*${currentBuild.currentResult}:* Job ${env.JOB_NAME} build ${env.BUILD_NUMBER} \n More info at: ${env.BUILD_URL}"
        }
        }    
    
}
def COLOR_MAP = [
    'SUCCESS': 'good',
    'FAILURE': 'danger',
    ]


pipeline {
    agent any
    
    tools {
        terraform 'Terraform'
    }
    
    environment {
        AWS_ACCESS_KEY_ID     = credentials('jenkins-aws-secret-key-id')
        AWS_SECRET_ACCESS_KEY = credentials('jenkins-aws-secret-access-key')
    }

    stages {
        stage('Git Checkout') {
            steps {
                echo 'Cloning project code base into jenkins'
                git branch: 'main', credentialsId: 'git-token', url: 'https://github.com/iam-faith/airbnb-infra-repo.git'
                sh 'ls'
            }
        }
        
        stage('Terraform Version') {
            steps {
                echo 'Verifying terraform version'
                sh 'terraform --version'
            }
        }
        
        stage('Terraform Init') {
            steps {
                echo 'Initializing project'
                sh 'terraform init'
            }
        }
        
        stage('Terraform Plan') {
            steps {
                echo 'Running Terraform plan'
                sh 'terraform plan'
            }
        }         
     
     
        stage('Terraform Apply/Destroy') {
            steps {
                sh 'terraform ${action} --auto-approve'
            }
        } 
       
    }
    
    post { 
        always { 
            echo 'I will always say Hello again!'
            slackSend channel: '#jjtech-champions-devops-team', color: COLOR_MAP[currentBuild.currentResult], message: "*${currentBuild.currentResult}:* Job ${env.JOB_NAME} build ${env.BUILD_NUMBER} \n More info at: ${env.BUILD_URL}"
        }
        }    
    
}
def COLOR_MAP = [
    'SUCCESS': 'good',
    'FAILURE': 'danger',
    ]


pipeline {
    agent any
    
    tools {
        terraform 'Terraform'
    }
    
    environment {
        AWS_ACCESS_KEY_ID     = credentials('jenkins-aws-secret-key-id')
        AWS_SECRET_ACCESS_KEY = credentials('jenkins-aws-secret-access-key')
    }

    stages {
        stage('Git Checkout') {
            steps {
                echo 'Cloning project code base into jenkins'
                git branch: 'main', credentialsId: 'git-token', url: 'https://github.com/iam-faith/airbnb-infra-repo.git'
                sh 'ls'
            }
        }
        
        stage('Terraform Version') {
            steps {
                echo 'Verifying terraform version'
                sh 'terraform --version'
            }
        }
        
        stage('Terraform Init') {
            steps {
                echo 'Initializing project'
                sh 'terraform init'
            }
        }
        
        stage('Terraform Plan') {
            steps {
                echo 'Running Terraform plan'
                sh 'terraform plan'
            }
        }         
     
     
        stage('Terraform Apply/Destroy') {
            steps {
                sh 'terraform ${action} --auto-approve'
            }
        } 
       
    }
    
    post { 
        always { 
            echo 'I will always say Hello again!'
            slackSend channel: '#jjtech-champions-devops-team', color: COLOR_MAP[currentBuild.currentResult], message: "*${currentBuild.currentResult}:* Job ${env.JOB_NAME} build ${env.BUILD_NUMBER} \n More info at: ${env.BUILD_URL}"
        }
        }    
    
}
def COLOR_MAP = [
    'SUCCESS': 'good',
    'FAILURE': 'danger',
    ]


pipeline {
    agent any
    
    tools {
        terraform 'Terraform'
    }
    
    environment {
        AWS_ACCESS_KEY_ID     = credentials('jenkins-aws-secret-key-id')
        AWS_SECRET_ACCESS_KEY = credentials('jenkins-aws-secret-access-key')
    }

    stages {
        stage('Git Checkout') {
            steps {
                echo 'Cloning project code base into jenkins'
                git branch: 'main', credentialsId: 'git-token', url: 'https://github.com/iam-faith/airbnb-infra-repo.git'
                sh 'ls'
            }
        }
        
        stage('Terraform Version') {
            steps {
                echo 'Verifying terraform version'
                sh 'terraform --version'
            }
        }
        
        stage('Terraform Init') {
            steps {
                echo 'Initializing project'
                sh 'terraform init'
            }
        }
        
        stage('Terraform Plan') {
            steps {
                echo 'Running Terraform plan'
                sh 'terraform plan'
            }
        }         
     
     
        stage('Terraform Apply/Destroy') {
            steps {
                sh 'terraform ${action} --auto-approve'
            }
        } 
       
    }
    
    post { 
        always { 
            echo 'I will always say Hello again!'
            slackSend channel: '#jjtech-champions-devops-team', color: COLOR_MAP[currentBuild.currentResult], message: "*${currentBuild.currentResult}:* Job ${env.JOB_NAME} build ${env.BUILD_NUMBER} \n More info at: ${env.BUILD_URL}"
        }
        }    
    
}
def COLOR_MAP = [
    'SUCCESS': 'good',
    'FAILURE': 'danger',
    ]


pipeline {
    agent any
    
    tools {
        terraform 'Terraform'
    }
    
    environment {
        AWS_ACCESS_KEY_ID     = credentials('jenkins-aws-secret-key-id')
        AWS_SECRET_ACCESS_KEY = credentials('jenkins-aws-secret-access-key')
    }

    stages {
        stage('Git Checkout') {
            steps {
                echo 'Cloning project code base into jenkins'
                git branch: 'main', credentialsId: 'git-token', url: 'https://github.com/iam-faith/airbnb-infra-repo.git'
                sh 'ls'
            }
        }
        
        stage('Terraform Version') {
            steps {
                echo 'Verifying terraform version'
                sh 'terraform --version'
            }
        }
        
        stage('Terraform Init') {
            steps {
                echo 'Initializing project'
                sh 'terraform init'
            }
        }
        
        stage('Terraform Plan') {
            steps {
                echo 'Running Terraform plan'
                sh 'terraform plan'
            }
        }         
     
     
        stage('Terraform Apply/Destroy') {
            steps {
                sh 'terraform ${action} --auto-approve'
            }
        } 
       
    }
    
    post { 
        always { 
            echo 'I will always say Hello again!'
            slackSend channel: '#jjtech-champions-devops-team', color: COLOR_MAP[currentBuild.currentResult], message: "*${currentBuild.currentResult}:* Job ${env.JOB_NAME} build ${env.BUILD_NUMBER} \n More info at: ${env.BUILD_URL}"
        }
        }    
    
}
def COLOR_MAP = [
    'SUCCESS': 'good',
    'FAILURE': 'danger',
    ]


pipeline {
    agent any
    
    tools {
        terraform 'Terraform'
    }
    
    environment {
        AWS_ACCESS_KEY_ID     = credentials('jenkins-aws-secret-key-id')
        AWS_SECRET_ACCESS_KEY = credentials('jenkins-aws-secret-access-key')
    }

    stages {
        stage('Git Checkout') {
            steps {
                echo 'Cloning project code base into jenkins'
                git branch: 'main', credentialsId: 'git-token', url: 'https://github.com/iam-faith/airbnb-infra-repo.git'
                sh 'ls'
            }
        }
        
        stage('Terraform Version') {
            steps {
                echo 'Verifying terraform version'
                sh 'terraform --version'
            }
        }
        
        stage('Terraform Init') {
            steps {
                echo 'Initializing project'
                sh 'terraform init'
            }
        }
        
        stage('Terraform Plan') {
            steps {
                echo 'Running Terraform plan'
                sh 'terraform plan'
            }
        }         
     
     
        stage('Terraform Apply/Destroy') {
            steps {
                sh 'terraform ${action} --auto-approve'
            }
        } 
       
    }
    
    post { 
        always { 
            echo 'I will always say Hello again!'
            slackSend channel: '#jjtech-champions-devops-team', color: COLOR_MAP[currentBuild.currentResult], message: "*${currentBuild.currentResult}:* Job ${env.JOB_NAME} build ${env.BUILD_NUMBER} \n More info at: ${env.BUILD_URL}"
        }
        }    
    
}
def COLOR_MAP = [
    'SUCCESS': 'good',
    'FAILURE': 'danger',
    ]


pipeline {
    agent any
    
    tools {
        terraform 'Terraform'
    }
    
    environment {
        AWS_ACCESS_KEY_ID     = credentials('jenkins-aws-secret-key-id')
        AWS_SECRET_ACCESS_KEY = credentials('jenkins-aws-secret-access-key')
    }

    stages {
        stage('Git Checkout') {
            steps {
                echo 'Cloning project code base into jenkins'
                git branch: 'main', credentialsId: 'git-token', url: 'https://github.com/iam-faith/airbnb-infra-repo.git'
                sh 'ls'
            }
        }
        
        stage('Terraform Version') {
            steps {
                echo 'Verifying terraform version'
                sh 'terraform --version'
            }
        }
        
        stage('Terraform Init') {
            steps {
                echo 'Initializing project'
                sh 'terraform init'
            }
        }
        
        stage('Terraform Plan') {
            steps {
                echo 'Running Terraform plan'
                sh 'terraform plan'
            }
        }         
     
     
        stage('Terraform Apply/Destroy') {
            steps {
                sh 'terraform ${action} --auto-approve'
            }
        } 
       
    }
    
    post { 
        always { 
            echo 'I will always say Hello again!'
            slackSend channel: '#jjtech-champions-devops-team', color: COLOR_MAP[currentBuild.currentResult], message: "*${currentBuild.currentResult}:* Job ${env.JOB_NAME} build ${env.BUILD_NUMBER} \n More info at: ${env.BUILD_URL}"
        }
        }    
    
}
def COLOR_MAP = [
    'SUCCESS': 'good',
    'FAILURE': 'danger',
    ]


pipeline {
    agent any
    
    tools {
        terraform 'Terraform'
    }
    
    environment {
        AWS_ACCESS_KEY_ID     = credentials('jenkins-aws-secret-key-id')
        AWS_SECRET_ACCESS_KEY = credentials('jenkins-aws-secret-access-key')
    }

    stages {
        stage('Git Checkout') {
            steps {
                echo 'Cloning project code base into jenkins'
                git branch: 'main', credentialsId: 'git-token', url: 'https://github.com/iam-faith/airbnb-infra-repo.git'
                sh 'ls'
            }
        }
        
        stage('Terraform Version') {
            steps {
                echo 'Verifying terraform version'
                sh 'terraform --version'
            }
        }
        
        stage('Terraform Init') {
            steps {
                echo 'Initializing project'
                sh 'terraform init'
            }
        }
        
        stage('Terraform Plan') {
            steps {
                echo 'Running Terraform plan'
                sh 'terraform plan'
            }
        }         
     
     
        stage('Terraform Apply/Destroy') {
            steps {
                sh 'terraform ${action} --auto-approve'
            }
        } 
       
    }
    
    post { 
        always { 
            echo 'I will always say Hello again!'
            slackSend channel: '#jjtech-champions-devops-team', color: COLOR_MAP[currentBuild.currentResult], message: "*${currentBuild.currentResult}:* Job ${env.JOB_NAME} build ${env.BUILD_NUMBER} \n More info at: ${env.BUILD_URL}"
        }
        }    
    
}
def COLOR_MAP = [
    'SUCCESS': 'good',
    'FAILURE': 'danger',
    ]


pipeline {
    agent any
    
    tools {
        terraform 'Terraform'
    }
    
    environment {
        AWS_ACCESS_KEY_ID     = credentials('jenkins-aws-secret-key-id')
        AWS_SECRET_ACCESS_KEY = credentials('jenkins-aws-secret-access-key')
    }

    stages {
        stage('Git Checkout') {
            steps {
                echo 'Cloning project code base into jenkins'
                git branch: 'main', credentialsId: 'git-token', url: 'https://github.com/iam-faith/airbnb-infra-repo.git'
                sh 'ls'
            }
        }
        
        stage('Terraform Version') {
            steps {
                echo 'Verifying terraform version'
                sh 'terraform --version'
            }
        }
        
        stage('Terraform Init') {
            steps {
                echo 'Initializing project'
                sh 'terraform init'
            }
        }
        
        stage('Terraform Plan') {
            steps {
                echo 'Running Terraform plan'
                sh 'terraform plan'
            }
        }         
     
     
        stage('Terraform Apply/Destroy') {
            steps {
                sh 'terraform ${action} --auto-approve'
            }
        } 
       
    }
    
    post { 
        always { 
            echo 'I will always say Hello again!'
            slackSend channel: '#jjtech-champions-devops-team', color: COLOR_MAP[currentBuild.currentResult], message: "*${currentBuild.currentResult}:* Job ${env.JOB_NAME} build ${env.BUILD_NUMBER} \n More info at: ${env.BUILD_URL}"
        }
        }    
    
}
def COLOR_MAP = [
    'SUCCESS': 'good',
    'FAILURE': 'danger',
    ]


pipeline {
    agent any
    
    tools {
        terraform 'Terraform'
    }
    
    environment {
        AWS_ACCESS_KEY_ID     = credentials('jenkins-aws-secret-key-id')
        AWS_SECRET_ACCESS_KEY = credentials('jenkins-aws-secret-access-key')
    }

    stages {
        stage('Git Checkout') {
            steps {
                echo 'Cloning project code base into jenkins'
                git branch: 'main', credentialsId: 'git-token', url: 'https://github.com/iam-faith/airbnb-infra-repo.git'
                sh 'ls'
            }
        }
        
        stage('Terraform Version') {
            steps {
                echo 'Verifying terraform version'
                sh 'terraform --version'
            }
        }
        
        stage('Terraform Init') {
            steps {
                echo 'Initializing project'
                sh 'terraform init'
            }
        }
        
        stage('Terraform Plan') {
            steps {
                echo 'Running Terraform plan'
                sh 'terraform plan'
            }
        }         
     
     
        stage('Terraform Apply/Destroy') {
            steps {
                sh 'terraform ${action} --auto-approve'
            }
        } 
       
    }
    
    post { 
        always { 
            echo 'I will always say Hello again!'
            slackSend channel: '#jjtech-champions-devops-team', color: COLOR_MAP[currentBuild.currentResult], message: "*${currentBuild.currentResult}:* Job ${env.JOB_NAME} build ${env.BUILD_NUMBER} \n More info at: ${env.BUILD_URL}"
        }
        }    
    
}
def COLOR_MAP = [
    'SUCCESS': 'good',
    'FAILURE': 'danger',
    ]


pipeline {
    agent any
    
    tools {
        terraform 'Terraform'
    }
    
    environment {
        AWS_ACCESS_KEY_ID     = credentials('jenkins-aws-secret-key-id')
        AWS_SECRET_ACCESS_KEY = credentials('jenkins-aws-secret-access-key')
    }

    stages {
        stage('Git Checkout') {
            steps {
                echo 'Cloning project code base into jenkins'
                git branch: 'main', credentialsId: 'git-token', url: 'https://github.com/iam-faith/airbnb-infra-repo.git'
                sh 'ls'
            }
        }
        
        stage('Terraform Version') {
            steps {
                echo 'Verifying terraform version'
                sh 'terraform --version'
            }
        }
        
        stage('Terraform Init') {
            steps {
                echo 'Initializing project'
                sh 'terraform init'
            }
        }
        
        stage('Terraform Plan') {
            steps {
                echo 'Running Terraform plan'
                sh 'terraform plan'
            }
        }         
     
     
        stage('Terraform Apply/Destroy') {
            steps {
                sh 'terraform ${action} --auto-approve'
            }
        } 
       
    }
    
    post { 
        always { 
            echo 'I will always say Hello again!'
            slackSend channel: '#jjtech-champions-devops-team', color: COLOR_MAP[currentBuild.currentResult], message: "*${currentBuild.currentResult}:* Job ${env.JOB_NAME} build ${env.BUILD_NUMBER} \n More info at: ${env.BUILD_URL}"
        }
        }    
    
}
def COLOR_MAP = [
    'SUCCESS': 'good',
    'FAILURE': 'danger',
    ]


pipeline {
    agent any
    
    tools {
        terraform 'Terraform'
    }
    
    environment {
        AWS_ACCESS_KEY_ID     = credentials('jenkins-aws-secret-key-id')
        AWS_SECRET_ACCESS_KEY = credentials('jenkins-aws-secret-access-key')
    }

    stages {
        stage('Git Checkout') {
            steps {
                echo 'Cloning project code base into jenkins'
                git branch: 'main', credentialsId: 'git-token', url: 'https://github.com/iam-faith/airbnb-infra-repo.git'
                sh 'ls'
            }
        }
        
        stage('Terraform Version') {
            steps {
                echo 'Verifying terraform version'
                sh 'terraform --version'
            }
        }
        
        stage('Terraform Init') {
            steps {
                echo 'Initializing project'
                sh 'terraform init'
            }
        }
        
        stage('Terraform Plan') {
            steps {
                echo 'Running Terraform plan'
                sh 'terraform plan'
            }
        }         
     
     
        stage('Terraform Apply/Destroy') {
            steps {
                sh 'terraform ${action} --auto-approve'
            }
        } 
       
    }
    
    post { 
        always { 
            echo 'I will always say Hello again!'
            slackSend channel: '#jjtech-champions-devops-team', color: COLOR_MAP[currentBuild.currentResult], message: "*${currentBuild.currentResult}:* Job ${env.JOB_NAME} build ${env.BUILD_NUMBER} \n More info at: ${env.BUILD_URL}"
        }
        }    
    
}checkov
def COLOR_MAP = [
    'SUCCESS': 'good',
    'FAILURE': 'danger',
    ]


pipeline {
    agent any
    
    tools {
        terraform 'Terraform'
    }
    
    environment {
        AWS_ACCESS_KEY_ID     = credentials('jenkins-aws-secret-key-id')
        AWS_SECRET_ACCESS_KEY = credentials('jenkins-aws-secret-access-key')
    }

    stages {
        stage('Git Checkout') {
            steps {
                echo 'Cloning project code base into jenkins'
                git branch: 'main', credentialsId: 'git-token', url: 'https://github.com/iam-faith/airbnb-infra-repo.git'
                sh 'ls'
            }
        }
        
        stage('Terraform Version') {
            steps {
                echo 'Verifying terraform version'
                sh 'terraform --version'
            }
        }
        
        stage('Terraform Init') {
            steps {
                echo 'Initializing project'
                sh 'terraform init'
            }
        }
        
        stage('Terraform Plan') {
            steps {
                echo 'Running Terraform plan'
                sh 'terraform plan'
            }
        }         
     
     
        stage('Terraform Apply/Destroy') {
            steps {
                sh 'terraform ${action} --auto-approve'
            }
        } 
       
    }
    
    post { 
        always { 
            echo 'I will always say Hello again!'
            slackSend channel: '#jjtech-champions-devops-team', color: COLOR_MAP[currentBuild.currentResult], message: "*${currentBuild.currentResult}:* Job ${env.JOB_NAME} build ${env.BUILD_NUMBER} \n More info at: ${env.BUILD_URL}"
        }
        }    
    
}
def COLOR_MAP = [
    'SUCCESS': 'good',
    'FAILURE': 'danger',
    ]


pipeline {
    agent any
    
    tools {
        terraform 'Terraform'
    }
    
    environment {
        AWS_ACCESS_KEY_ID     = credentials('jenkins-aws-secret-key-id')
        AWS_SECRET_ACCESS_KEY = credentials('jenkins-aws-secret-access-key')
    }

    stages {
        stage('Git Checkout') {
            steps {
                echo 'Cloning project code base into jenkins'
                git branch: 'main', credentialsId: 'git-token', url: 'https://github.com/iam-faith/airbnb-infra-repo.git'
                sh 'ls'
            }
        }
        
        stage('Terraform Version') {
            steps {
                echo 'Verifying terraform version'
                sh 'terraform --version'
            }
        }
        
        stage('Terraform Init') {
            steps {
                echo 'Initializing project'
                sh 'terraform init'
            }
        }
        
        stage('Terraform Plan') {
            steps {
                echo 'Running Terraform plan'
                sh 'terraform plan'
            }
        }         
     
     
        stage('Terraform Apply/Destroy') {
            steps {
                sh 'terraform ${action} --auto-approve'
            }
        } 
       
    }
    
    post { 
        always { 
            echo 'I will always say Hello again!'
            slackSend channel: '#jjtech-champions-devops-team', color: COLOR_MAP[currentBuild.currentResult], message: "*${currentBuild.currentResult}:* Job ${env.JOB_NAME} build ${env.BUILD_NUMBER} \n More info at: ${env.BUILD_URL}"
        }
        }    
    
}p-check CKV_AWS_79,CKV2_AWS_41
def COLOR_MAP = [
    'SUCCESS': 'good',
    'FAILURE': 'danger',
    ]


pipeline {
    agent any
    
    tools {
        terraform 'Terraform'
    }
    
    environment {
        AWS_ACCESS_KEY_ID     = credentials('jenkins-aws-secret-key-id')
        AWS_SECRET_ACCESS_KEY = credentials('jenkins-aws-secret-access-key')
    }

    stages {
        stage('Git Checkout') {
            steps {
                echo 'Cloning project code base into jenkins'
                git branch: 'main', credentialsId: 'git-token', url: 'https://github.com/iam-faith/airbnb-infra-repo.git'
                sh 'ls'
            }
        }
        
        stage('Terraform Version') {
            steps {
                echo 'Verifying terraform version'
                sh 'terraform --version'
            }
        }
        
        stage('Terraform Init') {
            steps {
                echo 'Initializing project'
                sh 'terraform init'
            }
        }
        
        stage('Terraform Plan') {
            steps {
                echo 'Running Terraform plan'
                sh 'terraform plan'
            }
        }         
     
     
        stage('Terraform Apply/Destroy') {
            steps {
                sh 'terraform ${action} --auto-approve'
            }
        } 
       
    }
    
    post { 
        always { 
            echo 'I will always say Hello again!'
            slackSend channel: '#jjtech-champions-devops-team', color: COLOR_MAP[currentBuild.currentResult], message: "*${currentBuild.currentResult}:* Job ${env.JOB_NAME} build ${env.BUILD_NUMBER} \n More info at: ${env.BUILD_URL}"
        }
        }    
    
}
def COLOR_MAP = [
    'SUCCESS': 'good',
    'FAILURE': 'danger',
    ]


pipeline {
    agent any
    
    tools {
        terraform 'Terraform'
    }
    
    environment {
        AWS_ACCESS_KEY_ID     = credentials('jenkins-aws-secret-key-id')
        AWS_SECRET_ACCESS_KEY = credentials('jenkins-aws-secret-access-key')
    }

    stages {
        stage('Git Checkout') {
            steps {
                echo 'Cloning project code base into jenkins'
                git branch: 'main', credentialsId: 'git-token', url: 'https://github.com/iam-faith/airbnb-infra-repo.git'
                sh 'ls'
            }
        }
        
        stage('Terraform Version') {
            steps {
                echo 'Verifying terraform version'
                sh 'terraform --version'
            }
        }
        
        stage('Terraform Init') {
            steps {
                echo 'Initializing project'
                sh 'terraform init'
            }
        }
        
        stage('Terraform Plan') {
            steps {
                echo 'Running Terraform plan'
                sh 'terraform plan'
            }
        }         
     
     
        stage('Terraform Apply/Destroy') {
            steps {
                sh 'terraform ${action} --auto-approve'
            }
        } 
       
    }
    
    post { 
        always { 
            echo 'I will always say Hello again!'
            slackSend channel: '#jjtech-champions-devops-team', color: COLOR_MAP[currentBuild.currentResult], message: "*${currentBuild.currentResult}:* Job ${env.JOB_NAME} build ${env.BUILD_NUMBER} \n More info at: ${env.BUILD_URL}"
        }
        }    
    
}
def COLOR_MAP = [
    'SUCCESS': 'good',
    'FAILURE': 'danger',
    ]


pipeline {
    agent any
    
    tools {
        terraform 'Terraform'
    }
    
    environment {
        AWS_ACCESS_KEY_ID     = credentials('jenkins-aws-secret-key-id')
        AWS_SECRET_ACCESS_KEY = credentials('jenkins-aws-secret-access-key')
    }

    stages {
        stage('Git Checkout') {
            steps {
                echo 'Cloning project code base into jenkins'
                git branch: 'main', credentialsId: 'git-token', url: 'https://github.com/iam-faith/airbnb-infra-repo.git'
                sh 'ls'
            }
        }
        
        stage('Terraform Version') {
            steps {
                echo 'Verifying terraform version'
                sh 'terraform --version'
            }
        }
        
        stage('Terraform Init') {
            steps {
                echo 'Initializing project'
                sh 'terraform init'
            }
        }
        
        stage('Terraform Plan') {
            steps {
                echo 'Running Terraform plan'
                sh 'terraform plan'
            }
        }         
     
     
        stage('Terraform Apply/Destroy') {
            steps {
                sh 'terraform ${action} --auto-approve'
            }
        } 
       
    }
    
    post { 
        always { 
            echo 'I will always say Hello again!'
            slackSend channel: '#jjtech-champions-devops-team', color: COLOR_MAP[currentBuild.currentResult], message: "*${currentBuild.currentResult}:* Job ${env.JOB_NAME} build ${env.BUILD_NUMBER} \n More info at: ${env.BUILD_URL}"
        }
        }    
    
}
def COLOR_MAP = [
    'SUCCESS': 'good',
    'FAILURE': 'danger',
    ]


pipeline {
    agent any
    
    tools {
        terraform 'Terraform'
    }
    
    environment {
        AWS_ACCESS_KEY_ID     = credentials('jenkins-aws-secret-key-id')
        AWS_SECRET_ACCESS_KEY = credentials('jenkins-aws-secret-access-key')
    }

    stages {
        stage('Git Checkout') {
            steps {
                echo 'Cloning project code base into jenkins'
                git branch: 'main', credentialsId: 'git-token', url: 'https://github.com/iam-faith/airbnb-infra-repo.git'
                sh 'ls'
            }
        }
        
        stage('Terraform Version') {
            steps {
                echo 'Verifying terraform version'
                sh 'terraform --version'
            }
        }
        
        stage('Terraform Init') {
            steps {
                echo 'Initializing project'
                sh 'terraform init'
            }
        }
        
        stage('Terraform Plan') {
            steps {
                echo 'Running Terraform plan'
                sh 'terraform plan'
            }
        }         
     
     
        stage('Terraform Apply/Destroy') {
            steps {
                sh 'terraform ${action} --auto-approve'
            }
        } 
       
    }
    
    post { 
        always { 
            echo 'I will always say Hello again!'
            slackSend channel: '#jjtech-champions-devops-team', color: COLOR_MAP[currentBuild.currentResult], message: "*${currentBuild.currentResult}:* Job ${env.JOB_NAME} build ${env.BUILD_NUMBER} \n More info at: ${env.BUILD_URL}"
        }
        }    
    
}
def COLOR_MAP = [
    'SUCCESS': 'good',
    'FAILURE': 'danger',
    ]


pipeline {
    agent any
    
    tools {
        terraform 'Terraform'
    }
    
    environment {
        AWS_ACCESS_KEY_ID     = credentials('jenkins-aws-secret-key-id')
        AWS_SECRET_ACCESS_KEY = credentials('jenkins-aws-secret-access-key')
    }

    stages {
        stage('Git Checkout') {
            steps {
                echo 'Cloning project code base into jenkins'
                git branch: 'main', credentialsId: 'git-token', url: 'https://github.com/iam-faith/airbnb-infra-repo.git'
                sh 'ls'
            }
        }
        
        stage('Terraform Version') {
            steps {
                echo 'Verifying terraform version'
                sh 'terraform --version'
            }
        }
        
        stage('Terraform Init') {
            steps {
                echo 'Initializing project'
                sh 'terraform init'
            }
        }
        
        stage('Terraform Plan') {
            steps {
                echo 'Running Terraform plan'
                sh 'terraform plan'
            }
        }         
     
     
        stage('Terraform Apply/Destroy') {
            steps {
                sh 'terraform ${action} --auto-approve'
            }
        } 
       
    }
    
    post { 
        always { 
            echo 'I will always say Hello again!'
            slackSend channel: '#jjtech-champions-devops-team', color: COLOR_MAP[currentBuild.currentResult], message: "*${currentBuild.currentResult}:* Job ${env.JOB_NAME} build ${env.BUILD_NUMBER} \n More info at: ${env.BUILD_URL}"
        }
        }    
    
}
def COLOR_MAP = [
    'SUCCESS': 'good',
    'FAILURE': 'danger',
    ]


pipeline {
    agent any
    
    tools {
        terraform 'Terraform'
    }
    
    environment {
        AWS_ACCESS_KEY_ID     = credentials('jenkins-aws-secret-key-id')
        AWS_SECRET_ACCESS_KEY = credentials('jenkins-aws-secret-access-key')
    }

    stages {
        stage('Git Checkout') {
            steps {
                echo 'Cloning project code base into jenkins'
                git branch: 'main', credentialsId: 'git-token', url: 'https://github.com/iam-faith/airbnb-infra-repo.git'
                sh 'ls'
            }
        }
        
        stage('Terraform Version') {
            steps {
                echo 'Verifying terraform version'
                sh 'terraform --version'
            }
        }
        
        stage('Terraform Init') {
            steps {
                echo 'Initializing project'
                sh 'terraform init'
            }
        }
        
        stage('Terraform Plan') {
            steps {
                echo 'Running Terraform plan'
                sh 'terraform plan'
            }
        }         
     
     
        stage('Terraform Apply/Destroy') {
            steps {
                sh 'terraform ${action} --auto-approve'
            }
        } 
       
    }
    
    post { 
        always { 
            echo 'I will always say Hello again!'
            slackSend channel: '#jjtech-champions-devops-team', color: COLOR_MAP[currentBuild.currentResult], message: "*${currentBuild.currentResult}:* Job ${env.JOB_NAME} build ${env.BUILD_NUMBER} \n More info at: ${env.BUILD_URL}"
        }
        }    
    
}
def COLOR_MAP = [
    'SUCCESS': 'good',
    'FAILURE': 'danger',
    ]


pipeline {
    agent any
    
    tools {
        terraform 'Terraform'
    }
    
    environment {
        AWS_ACCESS_KEY_ID     = credentials('jenkins-aws-secret-key-id')
        AWS_SECRET_ACCESS_KEY = credentials('jenkins-aws-secret-access-key')
    }

    stages {
        stage('Git Checkout') {
            steps {
                echo 'Cloning project code base into jenkins'
                git branch: 'main', credentialsId: 'git-token', url: 'https://github.com/iam-faith/airbnb-infra-repo.git'
                sh 'ls'
            }
        }
        
        stage('Terraform Version') {
            steps {
                echo 'Verifying terraform version'
                sh 'terraform --version'
            }
        }
        
        stage('Terraform Init') {
            steps {
                echo 'Initializing project'
                sh 'terraform init'
            }
        }
        
        stage('Terraform Plan') {
            steps {
                echo 'Running Terraform plan'
                sh 'terraform plan'
            }
        }         
     
     
        stage('Terraform Apply/Destroy') {
            steps {
                sh 'terraform ${action} --auto-approve'
            }
        } 
       
    }
    
    post { 
        always { 
            echo 'I will always say Hello again!'
            slackSend channel: '#jjtech-champions-devops-team', color: COLOR_MAP[currentBuild.currentResult], message: "*${currentBuild.currentResult}:* Job ${env.JOB_NAME} build ${env.BUILD_NUMBER} \n More info at: ${env.BUILD_URL}"
        }
        }    
    
}
def COLOR_MAP = [
    'SUCCESS': 'good',
    'FAILURE': 'danger',
    ]


pipeline {
    agent any
    
    tools {
        terraform 'Terraform'
    }
    
    environment {
        AWS_ACCESS_KEY_ID     = credentials('jenkins-aws-secret-key-id')
        AWS_SECRET_ACCESS_KEY = credentials('jenkins-aws-secret-access-key')
    }

    stages {
        stage('Git Checkout') {
            steps {
                echo 'Cloning project code base into jenkins'
                git branch: 'main', credentialsId: 'git-token', url: 'https://github.com/iam-faith/airbnb-infra-repo.git'
                sh 'ls'
            }
        }
        
        stage('Terraform Version') {
            steps {
                echo 'Verifying terraform version'
                sh 'terraform --version'
            }
        }
        
        stage('Terraform Init') {
            steps {
                echo 'Initializing project'
                sh 'terraform init'
            }
        }
        
        stage('Terraform Plan') {
            steps {
                echo 'Running Terraform plan'
                sh 'terraform plan'
            }
        }         
     
     
        stage('Terraform Apply/Destroy') {
            steps {
                sh 'terraform ${action} --auto-approve'
            }
        } 
       
    }
    
    post { 
        always { 
            echo 'I will always say Hello again!'
            slackSend channel: '#jjtech-champions-devops-team', color: COLOR_MAP[currentBuild.currentResult], message: "*${currentBuild.currentResult}:* Job ${env.JOB_NAME} build ${env.BUILD_NUMBER} \n More info at: ${env.BUILD_URL}"
        }
        }    
    
}
def COLOR_MAP = [
    'SUCCESS': 'good',
    'FAILURE': 'danger',
    ]


pipeline {
    agent any
    
    tools {
        terraform 'Terraform'
    }
    
    environment {
        AWS_ACCESS_KEY_ID     = credentials('jenkins-aws-secret-key-id')
        AWS_SECRET_ACCESS_KEY = credentials('jenkins-aws-secret-access-key')
    }

    stages {
        stage('Git Checkout') {
            steps {
                echo 'Cloning project code base into jenkins'
                git branch: 'main', credentialsId: 'git-token', url: 'https://github.com/iam-faith/airbnb-infra-repo.git'
                sh 'ls'
            }
        }
        
        stage('Terraform Version') {
            steps {
                echo 'Verifying terraform version'
                sh 'terraform --version'
            }
        }
        
        stage('Terraform Init') {
            steps {
                echo 'Initializing project'
                sh 'terraform init'
            }
        }
        
        stage('Terraform Plan') {
            steps {
                echo 'Running Terraform plan'
                sh 'terraform plan'
            }
        }         
     
     
        stage('Terraform Apply/Destroy') {
            steps {
                sh 'terraform ${action} --auto-approve'
            }
        } 
       
    }
    
    post { 
        always { 
            echo 'I will always say Hello again!'
            slackSend channel: '#jjtech-champions-devops-team', color: COLOR_MAP[currentBuild.currentResult], message: "*${currentBuild.currentResult}:* Job ${env.JOB_NAME} build ${env.BUILD_NUMBER} \n More info at: ${env.BUILD_URL}"
        }
        }    
    
}
def COLOR_MAP = [
    'SUCCESS': 'good',
    'FAILURE': 'danger',
    ]


pipeline {
    agent any
    
    tools {
        terraform 'Terraform'
    }
    
    environment {
        AWS_ACCESS_KEY_ID     = credentials('jenkins-aws-secret-key-id')
        AWS_SECRET_ACCESS_KEY = credentials('jenkins-aws-secret-access-key')
    }

    stages {
        stage('Git Checkout') {
            steps {
                echo 'Cloning project code base into jenkins'
                git branch: 'main', credentialsId: 'git-token', url: 'https://github.com/iam-faith/airbnb-infra-repo.git'
                sh 'ls'
            }
        }
        
        stage('Terraform Version') {
            steps {
                echo 'Verifying terraform version'
                sh 'terraform --version'
            }
        }
        
        stage('Terraform Init') {
            steps {
                echo 'Initializing project'
                sh 'terraform init'
            }
        }
        
        stage('Terraform Plan') {
            steps {
                echo 'Running Terraform plan'
                sh 'terraform plan'
            }
        }         
     
     
        stage('Terraform Apply/Destroy') {
            steps {
                sh 'terraform ${action} --auto-approve'
            }
        } 
       
    }
    
    post { 
        always { 
            echo 'I will always say Hello again!'
            slackSend channel: '#jjtech-champions-devops-team', color: COLOR_MAP[currentBuild.currentResult], message: "*${currentBuild.currentResult}:* Job ${env.JOB_NAME} build ${env.BUILD_NUMBER} \n More info at: ${env.BUILD_URL}"
        }
        }    
    
}
def COLOR_MAP = [
    'SUCCESS': 'good',
    'FAILURE': 'danger',
    ]


pipeline {
    agent any
    
    tools {
        terraform 'Terraform'
    }
    
    environment {
        AWS_ACCESS_KEY_ID     = credentials('jenkins-aws-secret-key-id')
        AWS_SECRET_ACCESS_KEY = credentials('jenkins-aws-secret-access-key')
    }

    stages {
        stage('Git Checkout') {
            steps {
                echo 'Cloning project code base into jenkins'
                git branch: 'main', credentialsId: 'git-token', url: 'https://github.com/iam-faith/airbnb-infra-repo.git'
                sh 'ls'
            }
        }
        
        stage('Terraform Version') {
            steps {
                echo 'Verifying terraform version'
                sh 'terraform --version'
            }
        }
        
        stage('Terraform Init') {
            steps {
                echo 'Initializing project'
                sh 'terraform init'
            }
        }
        
        stage('Terraform Plan') {
            steps {
                echo 'Running Terraform plan'
                sh 'terraform plan'
            }
        }         
     
     
        stage('Terraform Apply/Destroy') {
            steps {
                sh 'terraform ${action} --auto-approve'
            }
        } 
       
    }
    
    post { 
        always { 
            echo 'I will always say Hello again!'
            slackSend channel: '#jjtech-champions-devops-team', color: COLOR_MAP[currentBuild.currentResult], message: "*${currentBuild.currentResult}:* Job ${env.JOB_NAME} build ${env.BUILD_NUMBER} \n More info at: ${env.BUILD_URL}"
        }
        }    
    
}
def COLOR_MAP = [
    'SUCCESS': 'good',
    'FAILURE': 'danger',
    ]


pipeline {
    agent any
    
    tools {
        terraform 'Terraform'
    }
    
    environment {
        AWS_ACCESS_KEY_ID     = credentials('jenkins-aws-secret-key-id')
        AWS_SECRET_ACCESS_KEY = credentials('jenkins-aws-secret-access-key')
    }

    stages {
        stage('Git Checkout') {
            steps {
                echo 'Cloning project code base into jenkins'
                git branch: 'main', credentialsId: 'git-token', url: 'https://github.com/iam-faith/airbnb-infra-repo.git'
                sh 'ls'
            }
        }
        
        stage('Terraform Version') {
            steps {
                echo 'Verifying terraform version'
                sh 'terraform --version'
            }
        }
        
        stage('Terraform Init') {
            steps {
                echo 'Initializing project'
                sh 'terraform init'
            }
        }
        
        stage('Terraform Plan') {
            steps {
                echo 'Running Terraform plan'
                sh 'terraform plan'
            }
        }         
     
     
        stage('Terraform Apply/Destroy') {
            steps {
                sh 'terraform ${action} --auto-approve'
            }
        } 
       
    }
    
    post { 
        always { 
            echo 'I will always say Hello again!'
            slackSend channel: '#jjtech-champions-devops-team', color: COLOR_MAP[currentBuild.currentResult], message: "*${currentBuild.currentResult}:* Job ${env.JOB_NAME} build ${env.BUILD_NUMBER} \n More info at: ${env.BUILD_URL}"
        }
        }    
    
}
def COLOR_MAP = [
    'SUCCESS': 'good',
    'FAILURE': 'danger',
    ]


pipeline {
    agent any
    
    tools {
        terraform 'Terraform'
    }
    
    environment {
        AWS_ACCESS_KEY_ID     = credentials('jenkins-aws-secret-key-id')
        AWS_SECRET_ACCESS_KEY = credentials('jenkins-aws-secret-access-key')
    }

    stages {
        stage('Git Checkout') {
            steps {
                echo 'Cloning project code base into jenkins'
                git branch: 'main', credentialsId: 'git-token', url: 'https://github.com/iam-faith/airbnb-infra-repo.git'
                sh 'ls'
            }
        }
        
        stage('Terraform Version') {
            steps {
                echo 'Verifying terraform version'
                sh 'terraform --version'
            }
        }
        
        stage('Terraform Init') {
            steps {
                echo 'Initializing project'
                sh 'terraform init'
            }
        }
        
        stage('Terraform Plan') {
            steps {
                echo 'Running Terraform plan'
                sh 'terraform plan'
            }
        }         
     
     
        stage('Terraform Apply/Destroy') {
            steps {
                sh 'terraform ${action} --auto-approve'
            }
        } 
       
    }
    
    post { 
        always { 
            echo 'I will always say Hello again!'
            slackSend channel: '#jjtech-champions-devops-team', color: COLOR_MAP[currentBuild.currentResult], message: "*${currentBuild.currentResult}:* Job ${env.JOB_NAME} build ${env.BUILD_NUMBER} \n More info at: ${env.BUILD_URL}"
        }
        }    
    
}nfrastructure?'
def COLOR_MAP = [
    'SUCCESS': 'good',
    'FAILURE': 'danger',
    ]


pipeline {
    agent any
    
    tools {
        terraform 'Terraform'
    }
    
    environment {
        AWS_ACCESS_KEY_ID     = credentials('jenkins-aws-secret-key-id')
        AWS_SECRET_ACCESS_KEY = credentials('jenkins-aws-secret-access-key')
    }

    stages {
        stage('Git Checkout') {
            steps {
                echo 'Cloning project code base into jenkins'
                git branch: 'main', credentialsId: 'git-token', url: 'https://github.com/iam-faith/airbnb-infra-repo.git'
                sh 'ls'
            }
        }
        
        stage('Terraform Version') {
            steps {
                echo 'Verifying terraform version'
                sh 'terraform --version'
            }
        }
        
        stage('Terraform Init') {
            steps {
                echo 'Initializing project'
                sh 'terraform init'
            }
        }
        
        stage('Terraform Plan') {
            steps {
                echo 'Running Terraform plan'
                sh 'terraform plan'
            }
        }         
     
     
        stage('Terraform Apply/Destroy') {
            steps {
                sh 'terraform ${action} --auto-approve'
            }
        } 
       
    }
    
    post { 
        always { 
            echo 'I will always say Hello again!'
            slackSend channel: '#jjtech-champions-devops-team', color: COLOR_MAP[currentBuild.currentResult], message: "*${currentBuild.currentResult}:* Job ${env.JOB_NAME} build ${env.BUILD_NUMBER} \n More info at: ${env.BUILD_URL}"
        }
        }    
    
}
def COLOR_MAP = [
    'SUCCESS': 'good',
    'FAILURE': 'danger',
    ]


pipeline {
    agent any
    
    tools {
        terraform 'Terraform'
    }
    
    environment {
        AWS_ACCESS_KEY_ID     = credentials('jenkins-aws-secret-key-id')
        AWS_SECRET_ACCESS_KEY = credentials('jenkins-aws-secret-access-key')
    }

    stages {
        stage('Git Checkout') {
            steps {
                echo 'Cloning project code base into jenkins'
                git branch: 'main', credentialsId: 'git-token', url: 'https://github.com/iam-faith/airbnb-infra-repo.git'
                sh 'ls'
            }
        }
        
        stage('Terraform Version') {
            steps {
                echo 'Verifying terraform version'
                sh 'terraform --version'
            }
        }
        
        stage('Terraform Init') {
            steps {
                echo 'Initializing project'
                sh 'terraform init'
            }
        }
        
        stage('Terraform Plan') {
            steps {
                echo 'Running Terraform plan'
                sh 'terraform plan'
            }
        }         
     
     
        stage('Terraform Apply/Destroy') {
            steps {
                sh 'terraform ${action} --auto-approve'
            }
        } 
       
    }
    
    post { 
        always { 
            echo 'I will always say Hello again!'
            slackSend channel: '#jjtech-champions-devops-team', color: COLOR_MAP[currentBuild.currentResult], message: "*${currentBuild.currentResult}:* Job ${env.JOB_NAME} build ${env.BUILD_NUMBER} \n More info at: ${env.BUILD_URL}"
        }
        }    
    
}
def COLOR_MAP = [
    'SUCCESS': 'good',
    'FAILURE': 'danger',
    ]


pipeline {
    agent any
    
    tools {
        terraform 'Terraform'
    }
    
    environment {
        AWS_ACCESS_KEY_ID     = credentials('jenkins-aws-secret-key-id')
        AWS_SECRET_ACCESS_KEY = credentials('jenkins-aws-secret-access-key')
    }

    stages {
        stage('Git Checkout') {
            steps {
                echo 'Cloning project code base into jenkins'
                git branch: 'main', credentialsId: 'git-token', url: 'https://github.com/iam-faith/airbnb-infra-repo.git'
                sh 'ls'
            }
        }
        
        stage('Terraform Version') {
            steps {
                echo 'Verifying terraform version'
                sh 'terraform --version'
            }
        }
        
        stage('Terraform Init') {
            steps {
                echo 'Initializing project'
                sh 'terraform init'
            }
        }
        
        stage('Terraform Plan') {
            steps {
                echo 'Running Terraform plan'
                sh 'terraform plan'
            }
        }         
     
     
        stage('Terraform Apply/Destroy') {
            steps {
                sh 'terraform ${action} --auto-approve'
            }
        } 
       
    }
    
    post { 
        always { 
            echo 'I will always say Hello again!'
            slackSend channel: '#jjtech-champions-devops-team', color: COLOR_MAP[currentBuild.currentResult], message: "*${currentBuild.currentResult}:* Job ${env.JOB_NAME} build ${env.BUILD_NUMBER} \n More info at: ${env.BUILD_URL}"
        }
        }    
    
}
def COLOR_MAP = [
    'SUCCESS': 'good',
    'FAILURE': 'danger',
    ]


pipeline {
    agent any
    
    tools {
        terraform 'Terraform'
    }
    
    environment {
        AWS_ACCESS_KEY_ID     = credentials('jenkins-aws-secret-key-id')
        AWS_SECRET_ACCESS_KEY = credentials('jenkins-aws-secret-access-key')
    }

    stages {
        stage('Git Checkout') {
            steps {
                echo 'Cloning project code base into jenkins'
                git branch: 'main', credentialsId: 'git-token', url: 'https://github.com/iam-faith/airbnb-infra-repo.git'
                sh 'ls'
            }
        }
        
        stage('Terraform Version') {
            steps {
                echo 'Verifying terraform version'
                sh 'terraform --version'
            }
        }
        
        stage('Terraform Init') {
            steps {
                echo 'Initializing project'
                sh 'terraform init'
            }
        }
        
        stage('Terraform Plan') {
            steps {
                echo 'Running Terraform plan'
                sh 'terraform plan'
            }
        }         
     
     
        stage('Terraform Apply/Destroy') {
            steps {
                sh 'terraform ${action} --auto-approve'
            }
        } 
       
    }
    
    post { 
        always { 
            echo 'I will always say Hello again!'
            slackSend channel: '#jjtech-champions-devops-team', color: COLOR_MAP[currentBuild.currentResult], message: "*${currentBuild.currentResult}:* Job ${env.JOB_NAME} build ${env.BUILD_NUMBER} \n More info at: ${env.BUILD_URL}"
        }
        }    
    
}
def COLOR_MAP = [
    'SUCCESS': 'good',
    'FAILURE': 'danger',
    ]


pipeline {
    agent any
    
    tools {
        terraform 'Terraform'
    }
    
    environment {
        AWS_ACCESS_KEY_ID     = credentials('jenkins-aws-secret-key-id')
        AWS_SECRET_ACCESS_KEY = credentials('jenkins-aws-secret-access-key')
    }

    stages {
        stage('Git Checkout') {
            steps {
                echo 'Cloning project code base into jenkins'
                git branch: 'main', credentialsId: 'git-token', url: 'https://github.com/iam-faith/airbnb-infra-repo.git'
                sh 'ls'
            }
        }
        
        stage('Terraform Version') {
            steps {
                echo 'Verifying terraform version'
                sh 'terraform --version'
            }
        }
        
        stage('Terraform Init') {
            steps {
                echo 'Initializing project'
                sh 'terraform init'
            }
        }
        
        stage('Terraform Plan') {
            steps {
                echo 'Running Terraform plan'
                sh 'terraform plan'
            }
        }         
     
     
        stage('Terraform Apply/Destroy') {
            steps {
                sh 'terraform ${action} --auto-approve'
            }
        } 
       
    }
    
    post { 
        always { 
            echo 'I will always say Hello again!'
            slackSend channel: '#jjtech-champions-devops-team', color: COLOR_MAP[currentBuild.currentResult], message: "*${currentBuild.currentResult}:* Job ${env.JOB_NAME} build ${env.BUILD_NUMBER} \n More info at: ${env.BUILD_URL}"
        }
        }    
    
}
def COLOR_MAP = [
    'SUCCESS': 'good',
    'FAILURE': 'danger',
    ]


pipeline {
    agent any
    
    tools {
        terraform 'Terraform'
    }
    
    environment {
        AWS_ACCESS_KEY_ID     = credentials('jenkins-aws-secret-key-id')
        AWS_SECRET_ACCESS_KEY = credentials('jenkins-aws-secret-access-key')
    }

    stages {
        stage('Git Checkout') {
            steps {
                echo 'Cloning project code base into jenkins'
                git branch: 'main', credentialsId: 'git-token', url: 'https://github.com/iam-faith/airbnb-infra-repo.git'
                sh 'ls'
            }
        }
        
        stage('Terraform Version') {
            steps {
                echo 'Verifying terraform version'
                sh 'terraform --version'
            }
        }
        
        stage('Terraform Init') {
            steps {
                echo 'Initializing project'
                sh 'terraform init'
            }
        }
        
        stage('Terraform Plan') {
            steps {
                echo 'Running Terraform plan'
                sh 'terraform plan'
            }
        }         
     
     
        stage('Terraform Apply/Destroy') {
            steps {
                sh 'terraform ${action} --auto-approve'
            }
        } 
       
    }
    
    post { 
        always { 
            echo 'I will always say Hello again!'
            slackSend channel: '#jjtech-champions-devops-team', color: COLOR_MAP[currentBuild.currentResult], message: "*${currentBuild.currentResult}:* Job ${env.JOB_NAME} build ${env.BUILD_NUMBER} \n More info at: ${env.BUILD_URL}"
        }
        }    
    
}
def COLOR_MAP = [
    'SUCCESS': 'good',
    'FAILURE': 'danger',
    ]


pipeline {
    agent any
    
    tools {
        terraform 'Terraform'
    }
    
    environment {
        AWS_ACCESS_KEY_ID     = credentials('jenkins-aws-secret-key-id')
        AWS_SECRET_ACCESS_KEY = credentials('jenkins-aws-secret-access-key')
    }

    stages {
        stage('Git Checkout') {
            steps {
                echo 'Cloning project code base into jenkins'
                git branch: 'main', credentialsId: 'git-token', url: 'https://github.com/iam-faith/airbnb-infra-repo.git'
                sh 'ls'
            }
        }
        
        stage('Terraform Version') {
            steps {
                echo 'Verifying terraform version'
                sh 'terraform --version'
            }
        }
        
        stage('Terraform Init') {
            steps {
                echo 'Initializing project'
                sh 'terraform init'
            }
        }
        
        stage('Terraform Plan') {
            steps {
                echo 'Running Terraform plan'
                sh 'terraform plan'
            }
        }         
     
     
        stage('Terraform Apply/Destroy') {
            steps {
                sh 'terraform ${action} --auto-approve'
            }
        } 
       
    }
    
    post { 
        always { 
            echo 'I will always say Hello again!'
            slackSend channel: '#jjtech-champions-devops-team', color: COLOR_MAP[currentBuild.currentResult], message: "*${currentBuild.currentResult}:* Job ${env.JOB_NAME} build ${env.BUILD_NUMBER} \n More info at: ${env.BUILD_URL}"
        }
        }    
    
}
def COLOR_MAP = [
    'SUCCESS': 'good',
    'FAILURE': 'danger',
    ]


pipeline {
    agent any
    
    tools {
        terraform 'Terraform'
    }
    
    environment {
        AWS_ACCESS_KEY_ID     = credentials('jenkins-aws-secret-key-id')
        AWS_SECRET_ACCESS_KEY = credentials('jenkins-aws-secret-access-key')
    }

    stages {
        stage('Git Checkout') {
            steps {
                echo 'Cloning project code base into jenkins'
                git branch: 'main', credentialsId: 'git-token', url: 'https://github.com/iam-faith/airbnb-infra-repo.git'
                sh 'ls'
            }
        }
        
        stage('Terraform Version') {
            steps {
                echo 'Verifying terraform version'
                sh 'terraform --version'
            }
        }
        
        stage('Terraform Init') {
            steps {
                echo 'Initializing project'
                sh 'terraform init'
            }
        }
        
        stage('Terraform Plan') {
            steps {
                echo 'Running Terraform plan'
                sh 'terraform plan'
            }
        }         
     
     
        stage('Terraform Apply/Destroy') {
            steps {
                sh 'terraform ${action} --auto-approve'
            }
        } 
       
    }
    
    post { 
        always { 
            echo 'I will always say Hello again!'
            slackSend channel: '#jjtech-champions-devops-team', color: COLOR_MAP[currentBuild.currentResult], message: "*${currentBuild.currentResult}:* Job ${env.JOB_NAME} build ${env.BUILD_NUMBER} \n More info at: ${env.BUILD_URL}"
        }
        }    
    
}
def COLOR_MAP = [
    'SUCCESS': 'good',
    'FAILURE': 'danger',
    ]


pipeline {
    agent any
    
    tools {
        terraform 'Terraform'
    }
    
    environment {
        AWS_ACCESS_KEY_ID     = credentials('jenkins-aws-secret-key-id')
        AWS_SECRET_ACCESS_KEY = credentials('jenkins-aws-secret-access-key')
    }

    stages {
        stage('Git Checkout') {
            steps {
                echo 'Cloning project code base into jenkins'
                git branch: 'main', credentialsId: 'git-token', url: 'https://github.com/iam-faith/airbnb-infra-repo.git'
                sh 'ls'
            }
        }
        
        stage('Terraform Version') {
            steps {
                echo 'Verifying terraform version'
                sh 'terraform --version'
            }
        }
        
        stage('Terraform Init') {
            steps {
                echo 'Initializing project'
                sh 'terraform init'
            }
        }
        
        stage('Terraform Plan') {
            steps {
                echo 'Running Terraform plan'
                sh 'terraform plan'
            }
        }         
     
     
        stage('Terraform Apply/Destroy') {
            steps {
                sh 'terraform ${action} --auto-approve'
            }
        } 
       
    }
    
    post { 
        always { 
            echo 'I will always say Hello again!'
            slackSend channel: '#jjtech-champions-devops-team', color: COLOR_MAP[currentBuild.currentResult], message: "*${currentBuild.currentResult}:* Job ${env.JOB_NAME} build ${env.BUILD_NUMBER} \n More info at: ${env.BUILD_URL}"
        }
        }    
    
}-auto-approve'
def COLOR_MAP = [
    'SUCCESS': 'good',
    'FAILURE': 'danger',
    ]


pipeline {
    agent any
    
    tools {
        terraform 'Terraform'
    }
    
    environment {
        AWS_ACCESS_KEY_ID     = credentials('jenkins-aws-secret-key-id')
        AWS_SECRET_ACCESS_KEY = credentials('jenkins-aws-secret-access-key')
    }

    stages {
        stage('Git Checkout') {
            steps {
                echo 'Cloning project code base into jenkins'
                git branch: 'main', credentialsId: 'git-token', url: 'https://github.com/iam-faith/airbnb-infra-repo.git'
                sh 'ls'
            }
        }
        
        stage('Terraform Version') {
            steps {
                echo 'Verifying terraform version'
                sh 'terraform --version'
            }
        }
        
        stage('Terraform Init') {
            steps {
                echo 'Initializing project'
                sh 'terraform init'
            }
        }
        
        stage('Terraform Plan') {
            steps {
                echo 'Running Terraform plan'
                sh 'terraform plan'
            }
        }         
     
     
        stage('Terraform Apply/Destroy') {
            steps {
                sh 'terraform ${action} --auto-approve'
            }
        } 
       
    }
    
    post { 
        always { 
            echo 'I will always say Hello again!'
            slackSend channel: '#jjtech-champions-devops-team', color: COLOR_MAP[currentBuild.currentResult], message: "*${currentBuild.currentResult}:* Job ${env.JOB_NAME} build ${env.BUILD_NUMBER} \n More info at: ${env.BUILD_URL}"
        }
        }    
    
}
def COLOR_MAP = [
    'SUCCESS': 'good',
    'FAILURE': 'danger',
    ]


pipeline {
    agent any
    
    tools {
        terraform 'Terraform'
    }
    
    environment {
        AWS_ACCESS_KEY_ID     = credentials('jenkins-aws-secret-key-id')
        AWS_SECRET_ACCESS_KEY = credentials('jenkins-aws-secret-access-key')
    }

    stages {
        stage('Git Checkout') {
            steps {
                echo 'Cloning project code base into jenkins'
                git branch: 'main', credentialsId: 'git-token', url: 'https://github.com/iam-faith/airbnb-infra-repo.git'
                sh 'ls'
            }
        }
        
        stage('Terraform Version') {
            steps {
                echo 'Verifying terraform version'
                sh 'terraform --version'
            }
        }
        
        stage('Terraform Init') {
            steps {
                echo 'Initializing project'
                sh 'terraform init'
            }
        }
        
        stage('Terraform Plan') {
            steps {
                echo 'Running Terraform plan'
                sh 'terraform plan'
            }
        }         
     
     
        stage('Terraform Apply/Destroy') {
            steps {
                sh 'terraform ${action} --auto-approve'
            }
        } 
       
    }
    
    post { 
        always { 
            echo 'I will always say Hello again!'
            slackSend channel: '#jjtech-champions-devops-team', color: COLOR_MAP[currentBuild.currentResult], message: "*${currentBuild.currentResult}:* Job ${env.JOB_NAME} build ${env.BUILD_NUMBER} \n More info at: ${env.BUILD_URL}"
        }
        }    
    
}
def COLOR_MAP = [
    'SUCCESS': 'good',
    'FAILURE': 'danger',
    ]


pipeline {
    agent any
    
    tools {
        terraform 'Terraform'
    }
    
    environment {
        AWS_ACCESS_KEY_ID     = credentials('jenkins-aws-secret-key-id')
        AWS_SECRET_ACCESS_KEY = credentials('jenkins-aws-secret-access-key')
    }

    stages {
        stage('Git Checkout') {
            steps {
                echo 'Cloning project code base into jenkins'
                git branch: 'main', credentialsId: 'git-token', url: 'https://github.com/iam-faith/airbnb-infra-repo.git'
                sh 'ls'
            }
        }
        
        stage('Terraform Version') {
            steps {
                echo 'Verifying terraform version'
                sh 'terraform --version'
            }
        }
        
        stage('Terraform Init') {
            steps {
                echo 'Initializing project'
                sh 'terraform init'
            }
        }
        
        stage('Terraform Plan') {
            steps {
                echo 'Running Terraform plan'
                sh 'terraform plan'
            }
        }         
     
     
        stage('Terraform Apply/Destroy') {
            steps {
                sh 'terraform ${action} --auto-approve'
            }
        } 
       
    }
    
    post { 
        always { 
            echo 'I will always say Hello again!'
            slackSend channel: '#jjtech-champions-devops-team', color: COLOR_MAP[currentBuild.currentResult], message: "*${currentBuild.currentResult}:* Job ${env.JOB_NAME} build ${env.BUILD_NUMBER} \n More info at: ${env.BUILD_URL}"
        }
        }    
    
}
def COLOR_MAP = [
    'SUCCESS': 'good',
    'FAILURE': 'danger',
    ]


pipeline {
    agent any
    
    tools {
        terraform 'Terraform'
    }
    
    environment {
        AWS_ACCESS_KEY_ID     = credentials('jenkins-aws-secret-key-id')
        AWS_SECRET_ACCESS_KEY = credentials('jenkins-aws-secret-access-key')
    }

    stages {
        stage('Git Checkout') {
            steps {
                echo 'Cloning project code base into jenkins'
                git branch: 'main', credentialsId: 'git-token', url: 'https://github.com/iam-faith/airbnb-infra-repo.git'
                sh 'ls'
            }
        }
        
        stage('Terraform Version') {
            steps {
                echo 'Verifying terraform version'
                sh 'terraform --version'
            }
        }
        
        stage('Terraform Init') {
            steps {
                echo 'Initializing project'
                sh 'terraform init'
            }
        }
        
        stage('Terraform Plan') {
            steps {
                echo 'Running Terraform plan'
                sh 'terraform plan'
            }
        }         
     
     
        stage('Terraform Apply/Destroy') {
            steps {
                sh 'terraform ${action} --auto-approve'
            }
        } 
       
    }
    
    post { 
        always { 
            echo 'I will always say Hello again!'
            slackSend channel: '#jjtech-champions-devops-team', color: COLOR_MAP[currentBuild.currentResult], message: "*${currentBuild.currentResult}:* Job ${env.JOB_NAME} build ${env.BUILD_NUMBER} \n More info at: ${env.BUILD_URL}"
        }
        }    
    
}
def COLOR_MAP = [
    'SUCCESS': 'good',
    'FAILURE': 'danger',
    ]


pipeline {
    agent any
    
    tools {
        terraform 'Terraform'
    }
    
    environment {
        AWS_ACCESS_KEY_ID     = credentials('jenkins-aws-secret-key-id')
        AWS_SECRET_ACCESS_KEY = credentials('jenkins-aws-secret-access-key')
    }

    stages {
        stage('Git Checkout') {
            steps {
                echo 'Cloning project code base into jenkins'
                git branch: 'main', credentialsId: 'git-token', url: 'https://github.com/iam-faith/airbnb-infra-repo.git'
                sh 'ls'
            }
        }
        
        stage('Terraform Version') {
            steps {
                echo 'Verifying terraform version'
                sh 'terraform --version'
            }
        }
        
        stage('Terraform Init') {
            steps {
                echo 'Initializing project'
                sh 'terraform init'
            }
        }
        
        stage('Terraform Plan') {
            steps {
                echo 'Running Terraform plan'
                sh 'terraform plan'
            }
        }         
     
     
        stage('Terraform Apply/Destroy') {
            steps {
                sh 'terraform ${action} --auto-approve'
            }
        } 
       
    }
    
    post { 
        always { 
            echo 'I will always say Hello again!'
            slackSend channel: '#jjtech-champions-devops-team', color: COLOR_MAP[currentBuild.currentResult], message: "*${currentBuild.currentResult}:* Job ${env.JOB_NAME} build ${env.BUILD_NUMBER} \n More info at: ${env.BUILD_URL}"
        }
        }    
    
}
def COLOR_MAP = [
    'SUCCESS': 'good',
    'FAILURE': 'danger',
    ]


pipeline {
    agent any
    
    tools {
        terraform 'Terraform'
    }
    
    environment {
        AWS_ACCESS_KEY_ID     = credentials('jenkins-aws-secret-key-id')
        AWS_SECRET_ACCESS_KEY = credentials('jenkins-aws-secret-access-key')
    }

    stages {
        stage('Git Checkout') {
            steps {
                echo 'Cloning project code base into jenkins'
                git branch: 'main', credentialsId: 'git-token', url: 'https://github.com/iam-faith/airbnb-infra-repo.git'
                sh 'ls'
            }
        }
        
        stage('Terraform Version') {
            steps {
                echo 'Verifying terraform version'
                sh 'terraform --version'
            }
        }
        
        stage('Terraform Init') {
            steps {
                echo 'Initializing project'
                sh 'terraform init'
            }
        }
        
        stage('Terraform Plan') {
            steps {
                echo 'Running Terraform plan'
                sh 'terraform plan'
            }
        }         
     
     
        stage('Terraform Apply/Destroy') {
            steps {
                sh 'terraform ${action} --auto-approve'
            }
        } 
       
    }
    
    post { 
        always { 
            echo 'I will always say Hello again!'
            slackSend channel: '#jjtech-champions-devops-team', color: COLOR_MAP[currentBuild.currentResult], message: "*${currentBuild.currentResult}:* Job ${env.JOB_NAME} build ${env.BUILD_NUMBER} \n More info at: ${env.BUILD_URL}"
        }
        }    
    
}