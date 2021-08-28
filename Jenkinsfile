pipeline{

   agent any
   parameters{
               string(name:'COLOR',defaultValue:'Pink')
               choice(name:'ENV',choices:['staging','prod'])
   }
   stages{
     stage('string'){

      }
       steps{
          retry(5){           
          echo "$COLOR"
         }
       }
     }

   
     stage('choice'){
                    steps{

                           script{
                                  if(ENV=='prod'){
                                                   echo "env is $ENV"
                                       }
                       
                   }
            }

   }

}
