pipeline{

    agent any

    stages {

        stage('Git Checkout'){

            steps{

                script{

                   git branch: 'main', url: 'https://github.com/Bha298/3euraka.git'
                }
            }
        }
 
        stage('mvn install'){
            steps{
                script{
                        bat 'mvn clean install'   
                }
            }
        }
        
        
    }
}
