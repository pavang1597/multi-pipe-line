pipeline {
   agent any
   stages {
       stage('Build Code') {
           steps {
               sh """
               echo "Building Artifact for project samplewebapp"
			   """
               
           }
       }
       stage('Reading branch wise')
       {
       when
       {
       branch "feature*"
       }
       steps
       {
       echo " It is only for Feature branch"
       }
       }

       stage('Deploy  Code') {
	   
          steps {
               sh """
               echo "Deploying Code"
			   """
               
          }
<<<<<<< HEAD
      }
      }
      }
=======
       }
   }
}
>>>>>>> e9fbaf514072839d3da6b4b8ac7195a11965f9ea
