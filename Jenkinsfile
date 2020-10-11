
@Library('Lib') _

//myJenkinsfile(Name: 'master')

node('master') {
   stage('First') {
      def details = checkout scm
      env.GIT_DETAILS = details
      println "details.GIT_COMMIT"
      println details.GIT_COMMIT
      println env.GIT_DETAILS.getClass()
      println details.getClass()
      println scm.getClass()
      println scm.GIT_COMMIT
      bat script: 'set'
   }
}
