pipeline {
    /*
    * TODO: Implement pipeline stages/steps
    *   See documentation: https://www.jenkins.io/doc/book/pipeline/syntax/#stages
    */
    agent any 

    stages {
        stage('Build') {
            steps {
                // Run './gradlew assemble' command
                sh './gradlew assemble'
            }
        }
        stage('Test') {
            steps {
                // Run './gradlew test' command
                sh './gradlew test'
            }
        }
    }
}
