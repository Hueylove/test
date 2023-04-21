pipeline
{
    agent any
	parameters {
                    string(name: 'PERSON', defaultValue: 'Mr Jenkins', description: 'Who should I say hello to?')
                }
    stages{
           stage("first"){
               steps {
	                  /*def name='dylan'*/
                          echo 'hello ${params.PERSON}'
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
  
