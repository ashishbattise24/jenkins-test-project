pipeline{

   agent any
   parameters{
               string(name:'color',defaultValue:'Pink')
               choice(name:'env',choices:['staging','prod'])
   }
   stages{
     stage('string'){
       steps{
                     echo "$color"
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
