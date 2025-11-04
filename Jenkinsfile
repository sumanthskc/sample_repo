pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                
                git branch: 'feature', url: 'https://github.com/sumanthskc/sample_repo.git'
            }
        }

        stage('Run Python Script') {
            steps {
               
                sh 'python3 numbers.py'
            }
        }
    }
}
