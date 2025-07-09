pipeline {
    agent any
    stages {
        stage('Read File') {
            steps {
                script {
                    def content = readFile 'hello.txt'
                    echo "Content of hello.txt: ${content}"
                }
            }
        }
    }
}
