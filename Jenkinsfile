pipeline {
    agent any

    stages {
        stage('Run Python Script') {
            steps {
                script {
                    // If Python is installed and added to PATH
                    bat 'python simple.py'
                }
            }
        }
    }
}
