pipeline {
    agent any
    environment {
      PATH = "$PATH:/opt/apache-maven-3.9.1/bin"
    }
    
    stages {

        stage('CLEAN WORKSPACE') {
            steps {
                cleanWs()
            }
        }

        stage('CODE CHECKOUT') {
            steps {
                git 'https://github.com/pratyushsipu/devops_real_time_project_11-july-2023.git'
            }
        }
    }
}
