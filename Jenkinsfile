def GetPRID() {
    def scmHead = jenkins.scm.api.SCMHead.HeadByItem.findHead(currentBuild.rawBuild.getParent())
    
    def prId = scmHead.getId()
    
    return prId
}

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
            script {
                
                echo "${GetPRID()}"
            }
        }
    }
}
