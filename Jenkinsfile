pipeline {
   agent any
   stages {
     stage ('install') {
       steps { sh 'npm install' }
     }
     stage ('build') {
       steps { sh 'npm run-script build'}
     }
     stage ('test') {
       steps { sh 'npm test --code-coverage'}
     }
     stage ('lint') {
       steps { sh 'npm lint'}
     }
   }
 }