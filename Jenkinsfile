pipeline{
agent any

stages{
  stage('build job1'){
   steps{

      build(job:'job1',propagate: false)
      build('job2')
   }

  }

}

}
