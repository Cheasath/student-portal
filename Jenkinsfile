pipeline {
    agent any

    stages {
        stage('Clone Repo') {
            steps {
                git 'https://github.com/Cheasath/student-portal.git'
            }
        }

        stage('Deploy HTML') {
            steps {
                sh 'sudo cp index.html /var/www/html/index.html'
            }
        }
    }
}
