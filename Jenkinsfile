pipeline {
 agent any
 options{
 timestamps()
 }
 stages {
 stage("stage1") {
 failFast true
 parallel{
 stage('stage1job1'){
 steps{
 echo "stage1job1"
 sleep(10)
 }
 }
 stage('stage1job2'){
 steps{
 eecho "stage1job2"
 sleep(10)
 }
 } 
 stage('stage2job1'){
 steps{
 echo "stage2job1"
 sleep(5)
 }
 }
 stage('stage2job2'){
 steps{
 echo "stage2job2"
 sleep(5)
 }
 } 
 }
 }
 
 }
 }
