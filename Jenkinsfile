pipeline {
    agent any
    tools{
        maven 'local maven'
    }
    
    stages{
        stage('Init'){
            steps {
                echo "Testing......"
            }
<<<<<<< HEAD
            post {
                success {
                    echo '开始存档.....'
                    archiveArtifacts artifacts: '**/target/*.war'
                }
=======
        }
 	stage('Build'){
            steps {
                echo "Building......"
            }
        }
 	stage('Deploy'){
            steps {
                echo "Code Deployed."
>>>>>>> 1471cb9776f3d4ce8ee5b2fe6a3bcb2708774562
            }
        }
    }
}
