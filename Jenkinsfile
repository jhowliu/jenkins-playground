pipeline {
    agent any

    stages {
        stage("Init") {
            steps {           
                echo "Initializing"
            }
        }
        staget("build") {
            steps {           
                echo "Building"
            }
        }
    }

    post { 
        always { 
            echo "I will always say Hello again!"
        }
    }
}
