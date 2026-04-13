pipeline {
    agent any

    stages {
        stage('Clone') {
            steps {
                git 'https://github.com/Chiranth-Janardhan-moger/pipeline.git'
            }
        }

        stage('Run') {
            steps {
                sh 'python app.py'
            }
        }
    }
}
