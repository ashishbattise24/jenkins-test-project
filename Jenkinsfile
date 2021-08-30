pipeline{
agent any
stages{
 stage('build'){
    failFAST true
           parallel{
               stage('stage1job1'){
                  steps{
                        echo "stage1 and job1"
                        sleep(10)
                      }
               
               }
                stage('stage1job2'){
                     steps{

                            echo "stge1 and job2"
                            sleep(10)
                     }
 
                }
                stage('stage2job1'){
                   steps{
                          echo "stage2 and job1"
                          sleep(5)
                        }

                }
                stage('stage2job2'){
                    steps{

                            echo "stage2 and job2"
                            sleep(5)
                         }
                }

           }
 }
}

}
