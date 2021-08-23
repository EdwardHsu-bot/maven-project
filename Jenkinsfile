pipeline {
    agent any
    tools{
        maven "local maven"
        git "local git"
    }
    
    stages{
        stage('Build'){
            steps {
                sh 'mvn clean package'
            }
            post {
                success {
                    echo '开始存档.....'
                    archiveArtifacts artifacts: '**/target/*.war'
                }
            }
        }
    }
}