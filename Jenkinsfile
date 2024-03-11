pipeline {
    agent any

    parameters {
      booleanParam defaultValue: true, description: 'verify is the file is present', name: 'true'
      choice choices: ['CAMEROON', 'NIGERIA', 'GHANA', 'TOGO'], description: 'choose your country', name: 'NAME'
      string defaultValue: 'fritz', description: 'what your name', name: 'NAME'
      file description: 'upload the config file here', name: ''
    }


    stages {
        stage('Hello') {
            steps {
               sh'''
               echo my name is $NAME ,i am from $COUNTRY
               '''
                echo 'Hello World'
            }
        }
    }

    


    



}



