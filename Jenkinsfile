pipeline {
    agent any

    stages {
        stage('stage1') {
            steps {
                '''
                dir
                echo 'Hello World'
                python main.py
                '''
            }
        }
    }
}
