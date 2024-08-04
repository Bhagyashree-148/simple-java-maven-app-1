pipeline {
    agent any
    
    tools {
        maven 'maven 3.9.8'
        jdk 'java 21.0.4'
    }
    stages {
        stage('Build') { 
            steps {
                sh 'mvn -B -DskipTests clean package' 
            }
        }
    }
}

