pipeline{
 agent any
stages{

  stage('test'){
   steps{
       retry(3){
          echo 'hello retry 3'
       }
    }
 
   }
 }

}
