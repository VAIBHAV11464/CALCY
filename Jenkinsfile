pipeline {
    agent any
    stages {
        stage('Checkout Code') {
            steps {
                git branch: 'main', url: 'https://github.com/VAIBHAV11464/<your-calculator-repo>.git'
            }
        }
        stage('Build') {
            steps {
                bat 'python calculator.py'
            }
        }
    }
}
