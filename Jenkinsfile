pipeline {
    agent any

    stages {

        stage('Checkout Code') {
            steps {
                git branch: 'main',
                url: 'https://github.com/Ritesh-0305/data-visualization-tool'
            }
        }

        stage('Verify Files (Windows)') {
            steps {
                bat 'echo Checking files...'
                bat 'dir'
                bat '''
                IF NOT EXIST index.html (
                    echo index.html missing!
                    exit /b 1
                )
                '''
                bat 'echo Build Successful'
            }
        }

        stage('Archive Artifacts') {
            steps {
                archiveArtifacts artifacts: '**/*.*', fingerprint: true
            }
        }

        stage('Deploy') {
            steps {
                echo 'Static site ready (Local Deployment)'
            }
        }
    }
}
