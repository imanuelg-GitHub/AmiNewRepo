properties([parameters([string(defaultValue: 'Imanuel', name: 'NAME')]), pipelineTriggers([pollSCM('* * * * *')])])
node {
    stage("one") {
        git branch: 'main', url: 'https://github.com/imanuelg-GitHub/AmiNewRepo.git'
        bat "more 1.txt"
    }
}
