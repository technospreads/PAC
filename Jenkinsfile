pipeline {
 agent any
 environment {
  Subject = "pac"
  batct = "2"
}
parameters {
  choice choices: ['DEV', 'PROD', 'PRE-PROD'], description: 'Select your environment from dropdown list ', name: 'environment'
}
   stages {
		stage ("Testing variables"){
			steps {
				script {
					var1 =10
					println "Here is your user defined varaible value : ${var1} "
					println "Here is your environment varaible value : ${env.Subject} "
					println "Here is your environment varaible value : ${env.batct} "
					println "Here is your environment varaible value : ${env.BRANCH_NAME} "
					println "Here is your environment varaible value : ${env.BRANCH_NAME} "
					println "Here is your environment varaible value : ${env.BUILD_ID} "
					println "Here is your Globel varaible value : ${currentBuild.result} "
					println "Here is your Paramieterized  varaible value : ${params.environment} "
					}
				}
			}
		}
