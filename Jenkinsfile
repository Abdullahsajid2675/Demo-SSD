pipeline {
    agent any

    stages {
        stage('Unsafe Groovy Code') {
            steps {
                script {
                    new File("/etc/passwd").text
                }
            }
        }
    }
}
