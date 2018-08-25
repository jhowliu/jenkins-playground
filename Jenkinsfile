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
                echo " DAMNNN"
            }
        }
      
    }

    post { 
        always { 
            echo 'I will always say Hello again!'
        }

        success {
            pullRequest.addLabel("Build Successfully")
        }
    }
}
