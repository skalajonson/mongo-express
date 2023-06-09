pipeline {
    agent any
    
    stages {
        stage('create docker image mongo express') {
            steps {
                sh '''
                docker build -t chikibevchik/mongo:mongo-express .
                docker push chikibevchik/mongo:mongo-express
                '''
            }
        }
    }
}
