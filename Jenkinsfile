pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "Hello World"'
                sh 'printenv | sort'
                sh '''
                    echo "Multiline shell steps works too"
                    ls -lah
                    printenv | sort
                '''
            }
        }
    }
}
