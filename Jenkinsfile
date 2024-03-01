pipeline {
    agent { label 'agent_1' }

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
                sh 'g++ file.cpp -o file.gpp'
                sh './file.gpp'
            }
        }
    }
}
