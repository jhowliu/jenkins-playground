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
            script {

                pullRequest.addLabel("Build Successfully")
            }
        }
    }
}
