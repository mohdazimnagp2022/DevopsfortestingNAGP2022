pipeline{
    agent any
    	environment {
		notifyEmail ="mohd.azim@nagarro.com"
	}
    tools{
        maven 'Maven'
    }
    stages{
        stage("code checkout"){
            steps{
            bat "echo hello"
            }
        }   
        stage("code build"){
            steps{
            bat "mvn clean"
            }
        }
        stage("unit test"){
            steps{
            bat "mvn test"
            }
        }
        post{
        success{
            bat "echo success"
            }
        }
}
