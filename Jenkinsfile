pipeline {
   agent any
   stages {
      stage('Build') {
         steps {
            sh 'npm run build-hom'
         }
      }
      stage('Test') {
         steps {
            sh 'npm run test:coverage'
            sh 'npm run check:coverage'
         }
      }
      stage('Deploy') {
         steps {
            //
         }
      }
   }
}