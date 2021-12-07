pipeline {
	agent any
	tools {
		maven : "Maven"
	}
	stages{
		stage("Build") {
			steps {
				echo "Building application...";
				sh "mvn clean package"
			}
		}
	}
}
