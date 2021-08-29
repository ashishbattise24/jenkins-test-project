pipeline{
agent any

stages{
  stage('build job1'){
   steps{
     script{
      job_result = build(job:'job1',propagate: false).result
      build('job2')
      if(job_result=='FAILURE'){
      currentBuild.result='STABLE'
      }
    }
    }

  }

}

}
