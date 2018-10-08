pipeline {
    agent any

    tools {
        maven 'local_maven'
    }
    stages {
        stage ('Compile Stage') {
            steps {
                    sh 'mvn clean compile'
            }
        }

        stage ('Testing Stage') {
            steps {
                    sh 'mvn test'
            }
        }


    }
}