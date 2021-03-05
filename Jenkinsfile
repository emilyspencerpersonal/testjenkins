Jenkinsfile (Declarative Pipeline) 
pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                sh 'python --version'
                sh 'echo "Hello World"'
            }
        }
    stage("Build and start test image") {
        steps {
            sh '''echo "second step"
            ls -al
            '''
        }
    }
}
