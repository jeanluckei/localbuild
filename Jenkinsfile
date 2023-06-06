pipeline {
    agent { docker { image 'eclipse-temurin:17-jdk-jammy' } }
    stages {
        stage('build') {
            steps {
                sh 'gradle -v'
            }
        }
    }
}
