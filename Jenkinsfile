@Library("pipeline-shared-lib") _
//pipeline-shared-lib@dev burada branchi ekleyebiliyoruz.

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
