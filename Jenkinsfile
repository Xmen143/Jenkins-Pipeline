pipeline {
    agent any
        stages {
        stage('Build') {
            steps {
                echo "Hello Hello main${params.Branch}"
                echo "Starting Build #########################################################"
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
