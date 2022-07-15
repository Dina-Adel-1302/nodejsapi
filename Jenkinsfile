pipeline {
    agent any

    stages {
        stage('Getting repo files') {
            steps {
                git branch: '${GIT_BRANCH}', credentialsId: 'GitHub', url: 'https://github.com/Dina-Adel-1302/nodejsapi.git'
            }
        }
    }
}

