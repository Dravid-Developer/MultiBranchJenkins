pipeline { 
  
   agent any
   parameters {
        string(name: 'pipelineId', defaultValue: 'my-new-unique-id', description: 'The unique ID for the pipeline')
    }

   stages {
   
     stage('Install Dependencies') { 
        steps { 
           sh 'echo "npm install"' 
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
