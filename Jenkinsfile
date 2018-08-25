pipeline {
    agent any

    stages {
        stage('Init') {
            echo 'Initializing'
        }
        
        stage('echo') {
           echo 'ghprbActualCommit: ' $ghprbActualCommit
            echo 'ghprbActualCommitAuthor: ' $ghprbActualCommitAuthor
            echo 'ghprbActualCommitAuthorEmail: ' $ghprbActualCommitAuthorEmail
            echo 'ghprbPullDescription: ' $ghprbPullDescription
            echo 'ghprbPullId: ' $ghprbPullId
            echo 'ghprbPullLink: ' $ghprbPullLink
            echo 'ghprbPullTitle: ' $ghprbPullTitle
            echo 'ghprbSourceBranch: ' $ghprbSourceBranch
            echo 'ghprbTargetBranch: ' $ghprbTargetBranch
            echo 'sha1: ' $sha1   
            
        }
    }
}
