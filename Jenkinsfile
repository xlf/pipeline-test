pipeline {
    agent {
        dockerfile {
            filename 'Dockerfile-a'
        }
    }
    stages {
        stage('Test') {
            steps {
                sh 'yarn --version'
            }
        }
    }
}
