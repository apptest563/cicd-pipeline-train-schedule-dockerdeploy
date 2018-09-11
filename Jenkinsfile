pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'my test 3'
                sh './gradlew build --no-daemon'
                archiveArtifacts artifacts: 'dist/trainSchedule.zip'
            }
        }
    }
}
