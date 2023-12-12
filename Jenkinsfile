properties([pipelineTriggers([pollSCM('* * * * *')])])
node {
    stage("clone"){
        git branch: 'main', url: 'https://github.com/barda101/DevOpsBar.git'
    }
    stage("execute") {
    }
}