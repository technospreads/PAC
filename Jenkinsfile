pipeline {
    agent any
    environment {
        Subject = "pac"
        batch = "2" // Corrected from 'batct'
    }
    parameters {
        choice(choices: ['DEV', 'PROD', 'PRE-PROD'], description: 'Select your environment from dropdown list', name: 'environment')
    }
    stages {
        stage("Testing variables") {
            steps {
                script {
                    def var1 = 10
                    println "Here is your user-defined variable value: ${var1}"
                    println "Here is your environment variable value: ${env.Subject}"
                    println "Here is your environment variable value: ${env.batch}" // Corrected from 'batct'
                    println "Here is your environment variable value: ${env.BRANCH_NAME}"
                    println "Here is your environment variable value: ${env.BUILD_ID}"
                    println "Here is your Parameterized variable value: ${params.environment}"
                }
            }
        }
