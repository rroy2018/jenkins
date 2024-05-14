pipeline{
    agent any
    stages{
        stage('Demo'){
            steps{
                echo "Hello team"
                sh ('pwd')
            }
            
        }
    }
    post{
        always{
            cleanWs()
        }
    }
}
