properties([pipelineTriggers([pollSCM('* * * * *')])])
node {
    stage("clone"){
        git branch: 'master', url: 'https://github.com/barda101/DevOpsBar.git'
    }
    stage("execute") {
        echo "OK"
    }
}