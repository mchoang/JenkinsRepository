node {
stage ('Checkout') {
checkout ([$class: 'GitSCM', branches: [[name: '*/master]], doGenerateSubmoduleConfigurations: false, extensions: [], gitTool: 'Git', submoduleCfg: [], userRemoteConfigs: [url]: 'https://github.com/mchoang/JenkinsRepository']]])
def workspace = pwd ()
}
stage ('Static Code Analysis') {
echo "Static Code Analysis"
}
stage ('Build') 
{
echo "Build the Code"
}
stage ('Unit Testing') {
echo "Unit Testing"
}
stage ('Delivery')
{
echo "Deliver the Code"
}
}
