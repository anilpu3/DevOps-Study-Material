pipeline {
    agent any
    stages {
        stage('Run Tests') {
            parallel {
                stage('Test On Windows') {
                    
                    steps {
                        sh "echo stage 1"
                    }
                    
                }
                stage('Test On Linux') {
                    
                    steps {
                        sh "echo stage 2"
                    }
                   
                }
            }
        }
    }
}
