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
    }
  }
}
}
