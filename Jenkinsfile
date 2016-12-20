#!groovy

node ('base') {
	git https://github.com/eugeun/rpm-maven-plugin.git
	sh "${tool 'maven-3.3.9'}/bin/mvn -B clean verify"
	junit 'target/surefire-reports/*.xml'
}


