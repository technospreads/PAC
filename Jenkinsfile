def myfunc(int a=10, int b=20)
{
println " Here is your variable A value : ${a}, and varible B value : ${b} and here is your addition of variables : ${a+b}"
}

pipeline {
 agent any
   stages {
		stage ("Working with Functions"){
			steps {
				script {
					myfunc(100)
					myfunc(100,2020)
					myfunc(10,2000)
					}
				}
			}
		}
	}
