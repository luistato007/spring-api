pipeline {
    agent any
    stages {
        stage('Build') { 
            steps  {
                withMaven(maven: 'mvn') {
                    sh 'mvn -B -DskipTests clean package' 
                }
            }
        }
    }
}