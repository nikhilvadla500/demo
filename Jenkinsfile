@Library('my-hello-lib') _
pipeline {
    agent any
    stages {
        stage('Hello') {
            steps {
                hello()  // Calls shared function
            }
        }
    }
}
