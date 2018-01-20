pipeline {
    agent {
        dockerfile {
           filename 'Dockerfile-yarn'
       }
    }

    stages {
        stage('Test') {
            steps {
                    echo 'one'
                    sh 'yarn --version'
                    echo 'three'

            }
        }
    }
}
