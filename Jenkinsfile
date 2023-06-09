pipeline {
    agent any
        stages {
        stage('Build') {
            steps {
                echo "MAIN BRANCH --- JENKINS BUID PACKAGE"
                echo "Starting Build #########################################################"
                echo "PATH is: ${env.PATH}"
                sh 'java -version'
                sh 'mvn clean package'
            }
        }
    }
}
