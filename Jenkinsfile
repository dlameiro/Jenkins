pipeline {
    agent any
    stages {
        stage('Lambda-Option') {
            when {
                expression { params.Resources == "Lambda" }
            }
            steps {
                echo "Yoy have selected Lambda option"
            }
        }
        stage('EC2-Option') {
            when {
                expression { params.Resources == "EC2" }
            }
            steps {
                echo "Yoy have selected EC2 option"
            }
        }
        stage('VPC-Option') {
            when {
                expression { params.Resources == "VPC" }
            }
            steps {
                echo "Yoy have selected VPC option"
            }
        }
    }
}