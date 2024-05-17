pipeline {
    agent any

    stages {
        stage('Clone Repository') {
            steps {
                git 'https://github.com/yourusername/my-bash-script.git'
            }
        }
        stage('Execute Script') {
            steps {
                sh './run_ls.sh'
            }
        }
    }
}
