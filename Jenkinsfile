pipeline {
    agent any
    
    tools {
        maven 'Maven 3.9.8'
        jdk 'Java 21.0.0.0'
    }
    stages {
        stage('Build') { 
            steps {
                sh 'mvn -B -DskipTests clean package' 
            }
        }
    }
}

