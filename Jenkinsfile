pipeline {
    agent any

    stages {
        stage('stage1') {
            steps {
                bat "dir"
                echo 'Hello World'
                bat "python main.py"
            }
        }
    }
}
