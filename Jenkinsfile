@Library("pipeline-shared-lib") _

pipeline {
   agent any

   stages {
      stage('Build') {
         steps {
             script{
                 swissknife.printName 'John'
                }
           }
       }
   }
}
