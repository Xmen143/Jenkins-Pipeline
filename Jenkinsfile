pipeline {
    agent any
        stages {
        stage('Example') {
            steps {
                echo "Hello Hello main${params.Branch}"
                sh '''
                    java -version
                '''
            }
        }
    }
}
