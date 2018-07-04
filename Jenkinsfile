

node {

stage
('Checkout') {

checkout([$class: 'GitSCM', branches: [[name: '*/new-feature'], doGenerateSubmoduleConfigurations: false, extensions: [], gitTool: 'Git ', submoduleCfg: [], userRemoteConfigs: [[url: 'https://github.com/mchoang/JenkinsRepository.git']]])

}

     stage ('Hallo') {
          echo "1"
     }
     stage ('das') {
          echo "2"
     }
     stage ('ist') {
          echo "3"
     }
     stage ('ein') {
          echo "4"
     }
     stage ('Test') {
          echo "4"
     }
}



