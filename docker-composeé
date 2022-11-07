pipeline {


    agent any
    stages{
        stage('Checkout GIT'){
         steps {
             echo 'Pulling ...';
              git branch: 'master',
              url : 'https://github.com/Fourat888/DevopsFront.git'
         } 

        }


        

      
        stage('Building image docker-compose') {
          steps {

              sh "docker-compose up -d"
          }
        }

         
        	


	 

    }
}