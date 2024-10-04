def myfunc(int a=10, int b=20)
{
resul = a+b
	return resul
}

pipeline {
 agent any
   stages {
		stage ("Working with Functions"){
			steps {
				script {
					println myfunc()
					println myfunc(100)
					println myfunc(100,2020)
					println myfunc(10,2000)
					}
				}
			}
		}
	}
