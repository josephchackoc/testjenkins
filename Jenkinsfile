pipeline {
    agent {
        label "Agent1"
    }
    stages {
        stage('Test') {
            steps {
                sh '''
                env
                sleep 3600
                '''
            }
        }
        stage('Test2') {
            steps {
                sh '''
                env
                sleep 3600
                '''
            }
        }
    }
}
