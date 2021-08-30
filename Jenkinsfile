pipeline {
 agent any
 options{
 timestamps()
 }
 stages {
 stage("stage1") {
 steps{
 sh "ls -l"
 }
 post{ 
always{
 echo " action always "
}
changed{
 echo " action always Changed from previous state"
}
fixed{
 echo " action Fixed when previous state is failure"
}
 regression{
 echo " action when current state is fail/unstable/aborted , previous state is success"
}
aborted{
 echo " action always aborted"
}
failure{
 echo " action always failure"
}
success{
 echo " action always success"
}
unstable{
 echo " action unstable"
}
cleanup{
 echo " action similar like always , it is using to cleanup folder or 
workspace"
}
}
 
 }
 
 
 }
}
