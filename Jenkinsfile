pipeline{
    agent any 
    stages{
        stage("cloning ..."){
            steps{
                checkout([$class: 'GitSCM', branches: [[name: '*/main']], extensions: [], userRemoteConfigs: [[url: 'https://github.com/devopsPRO27/requests']]])

            }
        }
        stage("building ..."){
            steps{
                echo "========executing A========"
            }
        }
        stage("testing ..."){
            steps{
                echo "========executing A========"
            }
        }
    }
}
