pipeline{
        agent any
        stages{
                stage('Build-1'){
                steps{
                        bat 'mvn install'
                        }
                }
                stage('Run')
                steps{
                        bat 'java -jar target/java-project2-1.7'
                        }
                }
        }
}



