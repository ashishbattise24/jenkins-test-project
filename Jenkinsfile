pipeline {
 agent any
 stages {
 stage('Deploy') {
options { 
 retry(3)
 timeout(time: 5, unit: 'SECONDS') 
}
 steps {
 
 sh 'echo hello'
sleep(10)
 
 }
 }
 }
}
