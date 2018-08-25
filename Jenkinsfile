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
                echo "${scmHead.getSourceOwner()}"
                echo "${scmHead.getSourceRepo()}"
                echo "${scmHead.getId()}"
            }
        }
       
      
    }
    post { 
        always { 
            echo 'I will always say Hello again!'
        }
    }
}
