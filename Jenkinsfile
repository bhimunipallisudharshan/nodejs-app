pipeline { 
  
   agent any

   stages {
   
     stage('Install Dependencies') { 
        steps { 
           sh 'echo "installing npm packages..."' 
           git credentialsId: '2b1c00cf-2a02-4a7c-be83-2bf9ccc2ec88', url: 'https://github.com/bhimunipallisudharshan/nodejs-app.git'
        }
     }
     
     stage('Test') { 
        steps { 
           sh 'echo "testing application..."'
        }
      }

         stage("Deploy application") { 
         steps { 
           sh 'echo "deploying application..."'
         }

     }
  
   	}

   }
