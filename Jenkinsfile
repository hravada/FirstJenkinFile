pipeline {
    agent any
    stages {
        stage('check out') {
            steps {
                git credentialsId: '8bbdc524-aca4-4a58-ab49-4cbcce3015df', url: 'https://github.com/hravada/FirstJenkinFile.git'
            }
        }
    }
}
