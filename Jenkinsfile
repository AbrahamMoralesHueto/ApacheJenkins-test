pipeline {
    agent any

    stages {
        stage('Build frontend') {
            steps {
                sh 'cd /var/lib/jenkins/workspace/JenkinsTasksJob/tasks && npm install'
                sh 'npm run build'
                
            }
        }

        stage('Deploy') {
            steps{
                sh 'echo Deploy'
            }
        }
    }
}