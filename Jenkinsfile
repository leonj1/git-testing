node {
    def rootDir = pwd()

    def branchName = ${env.BRANCH_NAME}

    echo 'BRANCH.. ' + branchName
    load "${rootDir}@script/Jenkinsfile.${branchName}.Groovy"
}

