pipeline {
    agent { docker { image 'gradle:eclipse-temurin' } }
    stages {
        stage('build') {
            steps {
                sh 'gradle -v'
            }
        }
    }
}
