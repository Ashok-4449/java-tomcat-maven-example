pipeline
{
       agent any
       environment {
              PATH = "C:/apache-maven-3.6.2/bin:$PATH"
       }
       stages{
              stage("git"){
                     steps{
                            git 'https://github.com/Mani9257/java-tomcat-maven-example'
                     }
              }
              stage("build"){
                     withMaven(jdk: 'JAVA_HOME', maven: 'MAVEN-HOME') {
    // some block
}
                     steps{
                            bat "mvn clean install"
                     }
              }
       }
}
    
                            
       
