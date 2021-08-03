pipeline {
    agent any 
    
    environment {
        PROJECT_NAME = "NEPTUN"
        OWNER_NAME = "NICAT Isayev"
        SERVER_CREDENTIALS = credentials('server-cred')
    }
    
    stages {
        stage('Building') {
            steps {
                echo "START Build"
                echo "Building........"
                echo "END Build"
            }
        }
        
        stage('Testing') {
            steps {
                echo "START Test"
                echo "HELLO ${OWNER_NAME}"
                echo "HELLO ${PROJECT_NAME}"
                echo "TESTing........"
                echo "END TEST"
            }
        }
       
        stage('Deploy') {
            steps {
                echo "START Deploy"
                echo "HELLO ${OWNER_NAME}"
                echo "Deploying with ${SERVER_CREDENTIALS}"
                echo "Deploying........"
                echo "END Deploy"
            }
        }
 
    }
}
