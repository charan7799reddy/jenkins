pipeline{
    agent any

    stages{
        stage('checkout'){
            steps{
                checkout scm
            }
        }
    stage ('Build') {
            steps {
                sh 'mvn clean install' 
        }
            
    }
  }
}
