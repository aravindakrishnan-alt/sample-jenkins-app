pipeline {
	agent any

	stages{
		stage("Build") {
			steps {
				echo "Building application...";
				sh "mvn clean package"
			}
		}
	}
}
