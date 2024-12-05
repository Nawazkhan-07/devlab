pipeline {
    agent any
    options {
        // Timeout counter starts AFTER agent is allocated
        timeout(time: 1, unit: 'SECONDS')
    }
    stages {
        stage("build") {
            steps {
                echo "building the app"
            }
        }
       
        stage("test") {
            steps {
                echo "testing the app"
            }
        }
        
        stage("deploy") {
            steps {
                echo "deploying the app"
            }
        }
    }
}
