pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'test2'
                sh './gradlew build --no-daemon'
                archiveArtifacts artifacts: 'dist/trainSchedule.zip'
            }
        }
    }
}
