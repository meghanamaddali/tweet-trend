pipeline {
    agent {label 'maven'}
    
environment {
    PATH = "/opt/apache-maven-3.9.4/bin:$PATH"
}
    stages {
        stage('Build') {
            steps {
                // Example build step, replace with your build commands
                sh 'mvn clean deploy'
            }
        }
    }
}
