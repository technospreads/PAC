pipeline {
 agent any
   stages {
		stage ("Working with File operations"){
			steps {
				script {
					File obj1 = new File("/tmp/ravi.txt")
					println "here is your file content : ${obj1.text}"
					for ( line in obj1.readlines()){
					println "here is your file content : ${line}"
					}
					}
				}
			}
		}
	}
