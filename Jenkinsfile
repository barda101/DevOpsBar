properties([pipelineTriggers([pollSCM('* * * * *')])])
node {
    stage("clone"){
        git branch: 'main', url: 'https://github.com/avielb/DevOps0609.git'
    }
    stage("execute") {
        sh "python3 2.py"
    }
}