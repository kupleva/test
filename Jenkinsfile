pipeline {
    agent any
    environment {
        VER = '1.2.3'
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
            }
        }
    }
}
