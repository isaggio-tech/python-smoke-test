@Library('master-shared-lib')_

// Jenkinsfile (Declarative Pipeline) //
pipeline {
    agent { label 'python' }
    stages {
        stage('Version Check') {
            steps {
                sh 'python --version'
            }
        }
        stage('Shared Library Demo') {
            steps {
                echo 'Testing the Shared Library'
                helloWorld 'Hari !!!'   
            }
        }    
    }
}
