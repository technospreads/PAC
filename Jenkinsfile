def myfunc(int a, int b)
{
prinln " Here is your variable A value : ${a}, and varible B value : ${b} and here is your addition of variables : ${a+b}"
}

pipeline {
 agent any
   stages {
		stage ("Working with Functions"){
			steps {
				script {
					myfunc(10,20)
					}
				}
			}
		}
	}
