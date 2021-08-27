pipeline{

   agent any
   parameters{
               string(name:'color',defaultValue:'Pink')
               choice(name:'version',choices:['1.0','1.1'])
   }
   stages{
     stage('string'){
       steps{
                     echo "$color"
       }
     }

   }
}
