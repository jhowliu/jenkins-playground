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
                echo $ghprbPullId
            }
        }
      
    }
    post { 
        always { 
            echo 'I will always say Hello again!'
        }
    }
}
