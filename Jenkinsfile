node {
    def rootDir = pwd()

    def branchName = ${env.BRANCH_NAME}

    // Workaround for pipeline (not multibranches pipeline)
    def branchName = getCurrentBranch()

    echo 'BRANCH.. ' + branchName
    load "${rootDir}@script/Jenkinsfile.${branchName}.Groovy"
}

def getCurrentBranch () {
    return sh (
        script: 'git rev-parse --abbrev-ref HEAD',
        returnStdout: true
    ).trim()
}

