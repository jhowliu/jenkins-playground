pipeline {
    agent any

    stages {
        stage("Init") {
            steps {           
                echo "Initializing"
            }
        }

        stage("build") {
            steps {           
                echo "${BRANCH_NAME}"
            }
        }
      
    }
    post { 
        always { 
            echo 'I will always say Hello again!'
        }
    }
}
