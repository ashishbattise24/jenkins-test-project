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
              echo "$Version"
            }
          }
      }
    }
 
 }


