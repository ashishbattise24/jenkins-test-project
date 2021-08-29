pipeline{
agent any

stages{
  stage('build job1'){
   steps{

      build(job:'job1',propogate: false)
      build('job2')
   }

  }

}

}
