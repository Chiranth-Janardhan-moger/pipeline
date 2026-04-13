pipeline {
    agent any

    stages {
        stage('Clone') {
            steps {
                git 'https://github.com/Chiranth-Janardhan-moger/python-demo.git'
            }
        }

        stage('Run') {
            steps {
                bat 'python app.py'
            }
        }
    }
}
