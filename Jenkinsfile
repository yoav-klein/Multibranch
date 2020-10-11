
@Library('Lib') _

//myJenkinsfile(Name: 'master')

node('master') {
   stage('First') {
      def details = checkout scm
      env.GIT_DETAILS = details
      println details.GIT_COMMIT
      println details.getClass()
      bat script: 'set'
   }
}
