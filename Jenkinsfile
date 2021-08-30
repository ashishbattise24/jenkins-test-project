pipeline{
agent any
parameters{

  choice(name:'Nodes',
         choices:"Linux n Mac")
  choice(name:'Version',
         choices:['3.4','3.5','3.6'])
}
 stages{
   stage('build'){

      steps{
          script{
              echo "$Nodes"
              if(Version=='3.4'){
                      echo 'Version is 3.4'

              }else{

                 echo "Version is $Version"
              }
            }
          }
      }
    }
 
 }


