
@Library('Lib') _

//myJenkinsfile(Name: 'master')

node('master') {
   stage('First') {
      def details = checkout scm
      env.GIT_DETAILS = details
      println env.GIT_DETAILS.getClass()
      println details.getClass()
      pritnln scm.getClass()
      bat script: 'set'
   }
}
