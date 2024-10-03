pipeline{
    agent {
        label 'javajob'
    }

    stages{
        stage('Build'){
            steps{
                echo "Hello I'm in build stage"
                sh '''
                chmod 777 demo.sh
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
