
pipeline {
    agent any
    triggers {
cron('0 */2 * ? * *')
}
    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
        
        stage('Deploy') {
            steps {
                echo 'Welcome to Jenkins'
            }
        }
    }
}
