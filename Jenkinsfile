pipeline {
    agent any

    triggers {
         pollSCM('* * * * *')
     }

    stages {
        stage('Build'){
            sh 'mvn clean package'
        }
    }
}