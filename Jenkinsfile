node
{
    stage ('checkout')
    {
        checkout([$class: 'GitSCM', branches: [[name: '*/master']], doGenerateSubmoduleConfigurations: false, extensions: [], submoduleCfg: [], userRemoteConfigs: [[url: 'https://github.com/sibin-aeione/Sample.git']]])
    }
    stage ('Build')
    {
        echo "Build the code"
    }
}
