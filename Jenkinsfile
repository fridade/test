pipeline {
    agent any

    parameters {
     choice choices: ['DEV', 'QA', 'P PROD', 'PROD'], description: 'choose your env', name: 'ENVIRONMENT'
     string defaultValue: 'canary', description: 'choose the appropriate app', name: 'app'
    }





    stages {
        stage('build') {
            steps {
                echo 'Hello World'
            }
        }



        stage('test') {
            steps {
                echo 'Hello World'
            }
        }


        stage('deploy') {
            steps {
                echo 'Hello World'
            }
        }










    }





    
    









}
