pipeline{

   agent any
   parameters{
               string(name:'COLOR',defaultValue:'Pink')
               choice(name:'ENV',choices:['staging','prod'])
   }
   stages{
     stage('string'){
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
