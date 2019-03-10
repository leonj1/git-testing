#!groovy

node {
    def branchName = ${env.BRANCH_NAME}
    echo 'BRANCH.. ' + branchName
    def rootDir = pwd()
    load "${rootDir}@script/Jenkinsfile.${branchName}.Groovy"
}

