pipeline {
    agent any

    stages {
        stage('stage-1') {
            steps {
                sh '''
                date
                pwd
                echo "hello how r u"
                '''
            }
        }
        stage('Build-stage-2') {
            steps {
                echo 'Build process'
            }
        }
        stage('deploy-test-stage-3') {
            steps {
                echo 'Test Deploy'
            }
        }
        stage('deploy-prod-stage-4') {
            steps {
                echo 'Prod Deploy'
            }            
        }
    }
}
