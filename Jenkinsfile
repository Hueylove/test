pipeline
{
    agent any
    stages{
           stage("first"){
               steps {
	                  def name='dylan'
                          echo 'hello ${name}'
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
                                      echo 'always say goodbay finished'
                                  }
                     }
}
  
