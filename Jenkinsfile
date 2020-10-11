
@Library('Lib') _

//myJenkinsfile(Name: 'master')

pipeline
{
   agent { label 'master' }
   stages {
      stage('Print env'){
         steps {
            bat script: 'set'
         }
      }
   }
}
