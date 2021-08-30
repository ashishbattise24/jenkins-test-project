pipeline{
agent any
options{

timestamps()
}
stages{
  stage('build'){

             parallel{
                       stage('job1'){
                                steps{  
                                       echo "Job1"
                                       sleep(10)
                                     }
                        }
                        
                        stage('Job2'){
                                       steps{
                                             echo "Job2"
                                             sleep(10)
                                            }
                        }
 
                     }

           
  }

}
}
