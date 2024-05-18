pipeline {
    agent any

    stages {
        stage('Clone Repository') {
            steps {
                git 'https://github.com/A7madAdelll/cloudTask5.git'
            }
        }
        stage('Execute Script') {
            steps {
                bat './run_ls.bat'
            }
        }
    }
}
