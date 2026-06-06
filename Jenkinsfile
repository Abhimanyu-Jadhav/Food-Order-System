pipeline{

    agent any

    stages{
        stage('git checkout'){
            steps{
                  git branch: 'main',
                    url: 'https://github.com/Abhimanyu-Jadhav/Food-Order-System.git'
            }
        }

        stage('Build'){
            steps{
                sh 'mvn clean package'
            }
            
        }
    }
}