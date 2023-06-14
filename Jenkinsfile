pipeline {
    agent any
    stages {
        stage('HolaMundo') {
            when {
                expression { params.Resources == "Hola Mundo" }
            }
            steps {
                echo "Hola Mundo!"
            }
        }
        stage('Terraform') {
            when {
                expression { params.Resources == "Terraform" }
            }
            steps {
                echo "Terraform option selected"
                sh "terraform init"
            }
        }
    }
}