pipeline {
    agent any


    environment {
        DOCKERHUB_CREDENTIALS= credentials('docker hub')
        DOCKER_IMAGE_NAME = 'koushaliya/react01auto'
    }

  stages{
        stage('Checkout') {
            steps {
                // Checkout your code from your version control system
              git 'https://github.com/KoushaliyaSree/react01.git'
            }
        }
        
        
        

  }
    }