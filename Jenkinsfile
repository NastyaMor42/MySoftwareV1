properties([pipelineTriggers([pollSCM('*/30 * * * *')])])
node {
        stage("clone1"){
                git branch: 'main', url: 'https://github.com/NastyaMor42/MySoftwareV1.git'
    }
}
