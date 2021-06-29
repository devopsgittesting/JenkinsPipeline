pipeline {
  agent any 
  stages{
         stage("Build"){
            steps {
                      //scripts actually execute on jenkins server or jenkins agent
                   echo "building the application....."                   
           }
      }


         stage("Test"){
            steps {

                    //test execute script
              echo "Testing the application....." 
          }
      }

         stage("Deploy"){
            steps {
               // deployment script

             echo "Deploying the application....." 
          }
      }
   }
}
