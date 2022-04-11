pipeline {
    agent any
    tools {
        maven "run_time"
    }
    stages {
        stage ('Compile Stage') {
            
            steps {
                    //git 'https://github.com/YesvanthKannuri/game-of-life.git'
                    sh 'mvn clean compile'
            }
        }
    
        stage ('Testing Stage') {
            
            steps {
                    //git 'https://github.com/YesvanthKannuri/game-of-life.git'
                    sh 'mvn test'
            }
        }
    
        stage ('Deployment stage') {
            
            steps {
                    //git 'https://github.com/YesvanthKannuri/game-of-life.git'
                    sh 'mvn package'
            }
        }
    }
    
}
