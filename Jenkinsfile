pipeline {
    agent any
    environment {
        VER = '1.2.3'
        MY_CREDS = credentials('server-credentials')
    }
    
    stages {
        stage("build") {
            steps {
                echo 'Building...'
                echo "Version: ${VER}"
            }
        }

        stage("test") {
            steps {
                echo 'Testing...'
            }
        }
        
        stage("deploy") {
            steps {
                echo 'Deploying...'
                echo "MY_CREDS: ${MY_CREDS}"
            }
        }
    }
}
