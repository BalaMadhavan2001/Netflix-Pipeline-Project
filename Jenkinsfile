pipeline {
    agent any

    stages {
        stage('Clone repository') {
            steps {
                git 'https://github.com/BalaMadhavan2001/Netflix-Pipeline-Project.git/'
            }
        }

        stage('Build') {
            steps {
                sh 'mvn clean package'
            }
        }

        // Add more stages as needed (test, deploy, etc.)
    }
}
