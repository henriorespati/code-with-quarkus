pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh './mvnw -V clean install -DskipTests -DskipITs -DskipDocs'
            }
        }
    }
}