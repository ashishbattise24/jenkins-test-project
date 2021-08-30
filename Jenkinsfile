pipeline{
agent any
stages{
  stage('build'){

             parallel{
                       stage('job1'){
                                steps{  
                                       echo "Job1"
                                     }
                        }
                        
                        stage('Job2'){
                                       steps{
                                             echo "Job2"
                                            }
                        }
 
                     }

           
  }

}
}
