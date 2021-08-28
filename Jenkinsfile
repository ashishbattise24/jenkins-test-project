pipeline{

   agent any
   parameters{
               string(name:'COLOR',defaultValue:'Pink')
               choice(name:'env',choices:['staging','prod'])
   }
   stages{
     stage('string'){
       steps{
                     echo "$COLOR"
       }
     }

   }
     stage('choice'){
                    steps{

                           script{
                                  if(env=='prod'){
                                                   echo "env is $env"
                                       }
                       
                   }
            }

   }
}
