node('master') 
{
<<<<<<< HEAD
    stage('Continuous Download-master')
    {
        git 'https://github.com/nandha4083/maven.git'
    }
    stage('Continuous Build-master')
    {
        sh label: '', script: 'mvn package'
    }
    stage('Continuous Deployment-master')
    {
        sh label: '', script: 'scp /var/lib/jenkins/workspace/ScriptedPipeline/webapp/target/webapp.war msuser@172.31.35.82:/opt/tomcat/webapps/testapp1.war'
    }
    stage('Continuous Testing-master')
    {
        git 'https://github.com/selenium-saikrishna/FunctionalTesting.git'
        sh label: '', script: 'java -jar /var/lib/jenkins/workspace/ScriptedPipeline/testing.jar'
    }
    stage('Continuous Delivery-master')
    {
        sh label: '', script: 'scp /var/lib/jenkins/workspace/ScriptedPipeline/webapp/target/webapp.war msuser@172.31.4.160:/opt/tomcat/webapps/prodapp1.war'
    }
=======
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
>>>>>>> loans
}
