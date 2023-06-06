pipeline {
    agent { docker { image 'gradle:8.1.1-jdk17' } }
    stages {
        stage('build') {
            steps {
                sh 'gradle -v'
            }
        }
    }
}
