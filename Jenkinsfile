pipeline {
    agent any

    stages {
        stage('Environment') {
            steps {
                echo 'Hello from Jenkins!'

                sh 'hostname'
                sh 'whoami'
                sh 'pwd'
                sh 'git --version'
                sh 'python3 --version'
            }
        }
    }
}
