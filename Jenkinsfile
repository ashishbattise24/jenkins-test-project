pipeline{

   agent any
   parameters{
               string(name:'COLOR',defaultValue:'Pink')
               choice(name:'ENV',choices:['staging','prod'])
   }
   stages{
     stage('string'){
      options{
         retry(3)
         timeout(time:5, unit:'SECONDS')

      }
       steps{
                     echo "$COLOR"
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
}
