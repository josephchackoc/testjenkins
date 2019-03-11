pipeline {
    agent {
        docker { image 'node:7-alpine' }
    }
    stages {
        stage('Test') {
            steps {
                sh '''
                echo "some change"
                env
                node --version
                '''
            }
        }
    }
}
