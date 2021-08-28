pipeline{
 agent any
 options{
  retry(0)

 }
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
