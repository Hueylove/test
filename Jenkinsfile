pipeline
{
    agent any
    stages{
           stage("first"){
               steps {
	                  /*def name='dylan'*/
                          echo 'hello dylan'
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
  
