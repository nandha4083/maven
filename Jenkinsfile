node('master') 
{
    stage('Continuous Download')
    {
        git 'https://github.com/nandha4083/maven.git'
    }
    stage('Continuous Build')
    {
        sh label: '', script: 'mvn package'
    }
    stage('Continuous Deployment')
    {
        
    }
}
