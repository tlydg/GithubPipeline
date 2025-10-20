pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo "Pipeline job with Jenkinsfile (Windows)"
                bat 'echo Using Windows batch commands in Jenkinsfile'
                bat 'javac Hello.java'
                echo 'Build completed successfully.'
            }
        }

        stage('Run') {
            steps {
                echo "Running compiled Java file"
                bat 'echo Running Java file...'
                bat 'java Hello'
                echo 'Java file ran successfully!!!'
            }
        }
    }
}
