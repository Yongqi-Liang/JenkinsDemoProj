pipeline {
    agent any

    // 配置源码管理部分
    stages {
        stage('Checkout') {
            steps {
                // 使用 git 命令并指定 credentialsId
                git url: 'https://github.com/Yongqi-Liang/JenkinsDemoProj.git',
                    credentialsId: 'f2e2a744-f19f-45ce-aff5-5b9b5c0b1b18'
            }
        }
        stage('Test') {
            steps {
                sh 'echo "Hello from Jenkins machine!"'
            }
        }
    }
}
