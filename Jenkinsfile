pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git url: 'https://github.com/Yongqi-Liang/JenkinsDemoProj.git',
                    credentialsId: 'f2e2a744-f19f-45ce-aff5-5b9b5c0b1b18'
            }
        }
        stage('Test') {
            steps {
                sh '''
                echo "Starting test stage..."
                echo "Hello from Jenkins machine!"
                echo "Test stage completed."
                '''
            }
        }
    }
}
