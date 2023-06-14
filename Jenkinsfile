pipeline {
    agent any
    stages {
        stage('Lambda-Option') {
            when {
                expression { params.Resources == "Lambda" }
            }
            steps {
                echo "Hello Lambda World!"
            }
        }
        stage('EC2-Option') {
            when {
                expression { params.Resources == "EC2" }
            }
            steps {
                echo "Hello EC2 World!"
            }
        }
        stage('VPC-Option') {
            when {
                expression { params.Resources == "VPC" }
            }
            steps {
                echo "Hello VPC World!"
            }
        }
    }
}