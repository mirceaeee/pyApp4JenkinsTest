//Jenkinsfile (Declarative Pipeline)

/* Requires the Pipeline plugin */
pipeline {
   /* agent { docker { image 'python:3.12.4-alpine3.20' } }*/
    agent any
    stages {
        stage('build') {
            steps {
                sh 'python3 hw.py'
            }
        }
    }
}

