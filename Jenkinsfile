pipeline{
agent any
options{

timestamps()
}
stages{
 
  stage('build'){
        failFast true 
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
                             steps{
                                    ech0o "Stage2 and job1"

                                  }

                       }
                       stage('stage2job2'){

                           steps{

                                 echo "stage2 and job2"
 
                                }
                       }

                     }

           
  }

}
}
