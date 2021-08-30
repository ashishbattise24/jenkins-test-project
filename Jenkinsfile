pipeline{
agent any

options{

 timestamps()
}
triggers{
  pollSCM('* * * * *')

}
stages{

  stage('pollSCM'){

    steps{

          echo "This is PollSCM"
          git url: "https://github.com/kalaiarasan33/public.git"
    }
  }
}
}
