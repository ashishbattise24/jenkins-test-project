pipeline{
agent any
parameters{

  choice(name:'Nodes',
         choices:"Linux n Mac")
  choice(name:'Version',
         choices:'3.4')
}
 stages{
   stage('build'){

      steps{
              echo "$Nodes"
              echo "Version"
          }
      }
    }
 
 }


