pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                checkout([$class: 'GitSCM', branches: [[name: '*/master']], extensions: [], userRemoteConfigs: [[credentialsId: 'f53f31e9-47cd-4e69-a7b6-81ea0f45f849', url: 'https://github.com/srkiran40/srkiran40.git']]])
            }
        }
        stage('Build') {
            steps {
                sh 'mvn clean package'
            }
    }
    stage('Deploy') {
            steps {
                sshagent(['9f850361-5242-4c9e-8455-38a692877ba5']) {
    // some block
}
}
}
}
}
