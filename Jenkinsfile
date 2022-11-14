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
            echo "echo hello"
            }
        }   
        stage("code build"){
            steps{
           echo "mvn clean"
            }
        }
        stage("unit test"){
            steps{
            echo "mvn test"
            }
        }}}
