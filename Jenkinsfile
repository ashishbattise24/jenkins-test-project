pipeline{
agent any
options{

timestamps()
}
stages{
 
  stage('build'){
        failFast  
             parallel{
                       stage('stage1job1'){
                                steps{  
                                       echo "Job1"
                                       sleep(10)
                                     }
                        }
                        
                        stage('stage1Job2'){
                                       steps{
                                             echo "Job2"
                                             sleep(10)
                                            }
                        }
 
                       stage('stage2job1'){
                             state{
                                    echo "Stage2 and job1"

                                  }

                       }
                       stage('stage2job2'){

                           state{

                                 echo "stage2 and job2"
 
                                }
                       }

                     }

           
  }

}
}
