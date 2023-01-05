pipeline {
   
    agent any
   
    stages {

        stage('get code from github') {
            steps {
                echo 'Pulling...';
                git branch: 'main',
                url : 'https://github.com/AlloucheKarim/tp2amsdataKarim.git';
            }

            post {
                success {
                    echo ====++++success++++====
                }
               
                failure {
                    echo ====++++failed++++====
                }
            }
           
        }
           
    }
}