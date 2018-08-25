pipeline {
    agent any

    stages {
        stage("Init") {
            steps {           
                echo "Initializing"
                echo "HouseKeeper"
            }
        }
      
    }
    post { 
        always { 
            echo 'I will always say Hello again!'
        }
    }
}
