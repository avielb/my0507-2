properties([pipelineTriggers([pollSCM('* * * * *')])])
node {
    stage("clone"){
        git branch: 'main', url: 'https://github.com/avielb/my-0507-2.git'
    }
    stage("show files"){
        sh "ls -ltr"
        // bat "dir"
    }
}
