pipeline{
    agent any
    
    stages{
        stage('Checkout'){
            steps{
                echo('Build is complete')
                git 'https://github.com/Srividya-Ravichandran26/LeafTapsAutomation'
            }
        }
        stage('testing'){
            steps{
              echo('Testing is complete')
              bat 'mvn clean install'
            }
        }
    }
}
