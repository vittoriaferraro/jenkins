pipeline {
   agent any
   stages {
     stage ('install') {
       steps { sh 'npm install' }
     }
     stage ('build') {
       steps { sh 'ng build'}
     }
     stage ('test') {
       steps { sh 'ng test'}
     }
   }
 }