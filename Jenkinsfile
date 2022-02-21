pipeline {
    agent any
    
    environment {
        DEMO =  '1.3'
    }
    stages {
        stage('stage-1') {
            steps {
                echo "This is the build number $BUILD_NUMBER of $DEMO"
                sh  '''
                    echi "using a multiline shell"
                    chmod +x test.sh
                '''
            }
        }
    }
    
    
}
