pipeline {
    agent any
        stages {
        stage('Example') {
            steps {
                echo "Hello Hello main${params.Branch}"
                echo "PATH is: ${env.PATH}"
                sh '''
                    java -version
                    mvn clean package
                    echo "PATH is: ${env.PATH}"
                '''
            }
        }
    }
}
