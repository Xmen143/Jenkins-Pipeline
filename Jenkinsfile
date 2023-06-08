pipeline {
    agent any
        stages {
        stage('Example') {
            steps {
                echo "Hello Hello main${params.Branch}"
                echo "PATH is: ${env.PATH}"
                sh '''
                    java -version
                    echo "PATH is: ${env.PATH}"
                    javac BubbleSort.java
                '''
            }
        }
    }
}
