pipeline {
    agent any

    parameters {
     choice choices: ['DEV', 'QA', 'P PROD', 'PROD'], description: 'choose your env', name: 'ENVIRONMENT'
     string defaultValue: 'canary', description: 'choose the appropriate app', name: 'app'
     choice choices: ['ECR', 'DOKERHUB', 'NEXUS'], description: 'select the registry where you want to push your image', name: 'REGISTRY'
    }




    stages {
        stage('build') {
        when {
            expression {
            env.app == 'odilia'    

            }
        }
            steps {
                echo 'Hello World'
            }
        }



        stage('test') {
            when {
                env.REGISTRY == 'NEXUS'
            }
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
