pipeline{
    agent any

    stages{
        stage('Build'){
            steps{
                echo "Hello I'm in build stage"
                sh '''
            ./demo.sh
              '''  
            }
        }
        stage('Deliver'){
            steps{
                echo "Hello I'm in Deliver stage"
            }
        }
    }
}
