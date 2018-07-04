

node {

stage
('Checkout') {

checkout([$class: 'GitSCM', branches: [[name: '*/new-feature'], [name: '*/master']], doGenerateSubmoduleConfigurations: false, extensions: [], gitTool: 'Git ', submoduleCfg: [], userRemoteConfigs: [[url: 'https://github.com/mchoang/JenkinsRepository.git']]])

}

stage
('Static Code Analysis') {

     echo "Static Code Analysis"
     }
     stage ('Build')
     { echo "Build the code"
     }
     }



