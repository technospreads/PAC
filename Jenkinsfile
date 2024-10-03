pipeline {
 agent any
   stages {
		stage ("Working with conditions"){
			steps {
				script {
					a = input message: 'Please enter your variable A value ', parameters: [string(defaultValue: '10', description: 'a', name: 'a')]
					b = input message: 'Please enter your variable B value ', parameters: [string(defaultValue: '20', description: 'b', name: 'a')]
					if (a.toInteger() >= b.toInteger())
					
					{
					println "Here your A varibale value is big: ${a}"					
					}
					else
					{
					println "Here is your B varibale value is big: ${b}"
					}
				    }
				}
			}
		}
	}
