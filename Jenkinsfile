pipeline
{
    agent any
    stages{
           stage("first"){
               steps {
                          echo 'hello world'
               }
           }
	    stage("second"){
               steps {
                          echo 'build the project'
               }
           }

           stage("run test"){
               steps {
                           echo 'run test' 
               }
           }
           }
                post{
                           always{
                                      echo 'always say goodbay'
                                  }
                     }
}
  
