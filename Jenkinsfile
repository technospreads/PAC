pipeline {
 agent any
   stages {
		stage ("Working with File operations"){
			steps {
				script {
					File obj1 = new File("/tmp/ravi.txt")
					obj1.write("Hellow thi is checking my write function activity")
					println "here is your file content : ${obj1.text}"
					for ( line in obj1.readLines()){
					println "here is your file content : ${line}"
					}
					}
				}
			}
		}
	}
