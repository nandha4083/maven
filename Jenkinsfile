node('master') 
{
    stage('Continuous Download-loans')
    {
        git 'https://github.com/nandha4083/maven.git'
    }
    stage('Continuous Build-loans')
    {
        sh label: '', script: 'mvn package'
    }
    stage('Continuous Deployment-loans')
    {
        sh label: '', script: 'scp /var/lib/jenkins/workspace/ScriptedPipeline/webapp/target/webapp.war msuser@172.31.35.82:/opt/tomcat/webapps/testapp1.war'
    }
}
