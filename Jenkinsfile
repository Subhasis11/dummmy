node {
    stage('Build') {
        sh 'mvn clean package'
    
    stage('Deploy') {
        sh 'scp webapp/target/webapp.war ubuntu@172.31.30.56:/var/lib/tomcat10/webapps/testting.war'
    }
}
