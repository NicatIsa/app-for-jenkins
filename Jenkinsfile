pipeline {
    agent any 
    
    environment {
        PROJECT_NAME = "NEPTUN"
        OWNER_NAME = "NICAT Isayev"
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
    }
}
