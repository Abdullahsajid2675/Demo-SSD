pipeline {
    agent any

    stages {
        stage('Credentials Test') {
            steps {
                withCredentials([string(credentialsId: 'mysecret', variable: 'API')]) {
                    echo "Using secret safely"
                }
            }
        }
    }
}
