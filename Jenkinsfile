pipeline {
    agent any

    stages {
        stage('Pulling Repo files') {
            steps {
                git branch: "${GIT_BRANCH}", credentialsId: 'gitHup', url: 'https://github.com/HaythamMohamd/simple_nodejs_app.git'
            }
        }
        stage('stage1') {
            steps {
                sh '''
                    ls
                    date
                    
                '''
            }
        }
        
    }
}
