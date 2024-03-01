pipeline {
    agent any

    tools 
    {
        nodejs 'node'
    }

    stages {
        stage('Checkout') {
            steps {
                // Checkout your code from your version control system
              git 'https://github.com/KoushaliyaSree/react01.git'
            }
        }
        
        stage('Install Dependencies') {
            steps {
                // Install Node.js and npm if necessary
                sh 'npm install'
            }
        }
        
        stage('Build') {
            steps {
                // Build your React application
                sh 'npm run build'
            }
        }
        
        stage('Test') {
            steps {
                // Run tests if you have them
                echo'npm test'
            }
        }

        stage('Deploy') {
            steps {
                // Deploy your application to a server
                // You may need to adjust this step based on your deployment strategy
                echo 'npm run deploy'
            }
        }
    }
    
   
}
