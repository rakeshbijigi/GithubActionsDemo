
pipeline {
    agent any
    options {
        // Timeout counter starts AFTER agent is allocated
        timeout(time: 1, unit: 'SECONDS')
    }
    stages {
        stage('Example') {
            steps {
                echo 'Hello World'

		echo 'this is first multibranch pipeline'
		echo 'triggering pipeline using poll scm'    
            }
        }
    }
}
