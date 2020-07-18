node
{
    stage('Checkout')
    {
        checkout([$class: 'GitSCM', branches: [[name: '*/master']], doGenerateSubmoduleConfigurations: false, extensions: [], submoduleCfg: [], userRemoteConfigs: [[url: 'https://github.com/abhilashchoudhary0001/demo.git']]])
    }
    
    stage('Test')
    {
        echo "This is test"
        
    }
    
    stage('Deploy')
    {
        echo " This is deploy"
    }
}
